## image responsive

- width:100%
- max-width:750px;
- min-width:200px;
- set height to ***auto***

### bootstrap image classes

- `img-responsive`, standard img responsive class
- `img-rounded`, adds a little bit of border radius to image
- `img-circle`, makes it a full circle
- `img-thumbnail`, gives img look often associated with thumbnails

```
  ex:
    .carousel-inner > .item > a > img, carousel-inner > .item > img,
    .img-responsive, .thumbnail a > img, .thumbnail > img {
      display: block;
      max-width:100%;
      height:auto;

    }


```


<kbd>thumbnail image</kbd>

```
  ex:
    <div class="container">
     <div id="row">
       <img src= "https://s3-us..jpg" class="col-sm-6 col-md-4 col-lg-2 img-thumbnail">
       <img src= "https://s3-us..jpg" class="col-sm-6 col-md-4 col-lg-2 img-thumbnail">
       <img src= "https://s3-us..jpg" class="col-sm-6 col-md-4 col-lg-2 img-thumbnail">
     </div>
    </div>

```

## tables

- .table, adds some padding and horizontal dividers
- .table-striped, zebra stripes where `odd` rows have light color
- .table-bordered, add borders to table and cells
- .table-hover, adds hover state styling

- there is only one breakpoint for responsive tables
- default(under 768px) allows horizontal scrolling
- anything over 768 falls to default view - no scrolling at the bottom

- also possible to style individual elements:
  + active, success, info
  + warning, danger


```
  ex: for table responsive

  <div class="table-responsive">
    <table class="table table-stripped table-bordered table-hover">
     <tr class="warning">

   `note` -> you add `table-responsive` class to the parent element. 


```


















