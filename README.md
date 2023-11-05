1. Buatlah Forlder baru dengan nama Lab6_CSS_framework


```html
<!DOCTYPE html>
<html lang="en" >
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>lab6_css_framework</title>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>

```

2. Membuat Navbar Sederhana

```html
           <!--NAVBAR-->
            <div class="jumbotron jumbotron-fluid bg-light pb-2 mb-1">
              <div class="container">
                <h1 class="display-4">Layout Sederhana</h1>
              </div>
            </div>
            
            <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
              <a class="navbar-brand" href="#">Navbar</a>
              <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Article</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link">contact</a>
                  </li>
                </ul>
              </div>
            </nav>
```
Output :

![image](https://github.com/twn304/lab6web/assets/115573041/b1527976-71ca-4efa-8a9b-1a70611e4b3b)



3. 

```html
        <!--JUMBOTRON-->
    <div class="jumbotron">
    <h1 class="display-4">Hello, world!</h1>
    <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat.</p>
    <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
    </div>
     <div class="d-flex p-2">
    <div class="p-2">
```
Output :

![image-1](https://github.com/twn304/lab6web/assets/115573041/1fc24fb7-2fce-4bb1-8712-ab9a4daebce8)


4. Card 1
```html
   <!--CARDS-->
    <div class="row" >
      <div class="col">
      <div class="card pt-3">
        <img src="120px.png" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h5 class="card-title text-center">Heading</h5>
          <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-3">View Detail</a></p>
        </div>
      </div>
      </div>
      <div class="col">
      <div class="card pt-3">
        <img src="120px.png" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h5 class="card-title text-center">Heading</h5>
          <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-3">View Detail</a></p>
        </div>
      </div>
      </div>
      <div class="col">
      <div class="card pt-3">
        <img src="120px.png" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h5 class="card-title text-center">Heading</h5>
          <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-3">View Detail</a></p>
        </div>
      </div>
      </div>
      </div>

<style css >
  .card-img-top{
  width: 120px;
  align-self: center;
}

footer {
    clear:both;
  background-color:#1d1d1d; 
  padding:20px;
  color:#eee;
}

</style>
<hr>
```
Output :

![image-2](https://github.com/twn304/lab6web/assets/115573041/2e283ab1-641b-4a99-9162-bfab7dfba0b8)



5.List Grop pada samping kanan card 1
```html 
<!--LIST GROUP-->
  <div class="col">
  <div class="list-group">
    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
      Widget Header
    </a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
  </div>
  <div class="list-group mt-3">
    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
      Widget Text
    </a>
    <span class="list-group-item list-group-item-action">Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu.
      Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</span>
  </div>
</div>  
</div>
</div>
```
Output :

![image-3](https://github.com/twn304/lab6web/assets/115573041/60869e53-30c6-433b-bb89-1cd739630d41)


7. Card ke 2

```html
  <!--CARDS 2-->
  <div class="mt-3 mb-5">
    <h2>First Featurette Heading</h2>
    <div class="row no-gutters">
      <div class="col-md-3">
        <img src="150.jpg" class="card-img-top rounded-square" alt="...">
      </div>
      <div class="col-md-8">
        <div class="card-body">
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
        </div>
      </div>
    </div>
  </div>
<hr>
  <div class="mt-5">
    <h2>First Featurette Heading</h2>
    <div class="row">
      <div class="col-md-8">
        <div class="card-body">
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
        </div>
      </div>
      <div class="col-md-3">
        <img src="150.jpg" class="card-img-top rounded-square" alt="...">
      </div>
    </div>
  </div>

</div>
<div class="p-2">

```
Output :

![image-4](https://github.com/twn304/lab6web/assets/115573041/15d8d016-e7aa-4ebd-bbcf-4b90c18149d6)


Tampilan Full 
![image-5](https://github.com/twn304/lab6web/assets/115573041/b0b63367-c354-4384-aa9d-d28c70a92d53)
