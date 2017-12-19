## bootstrap grid system

- 12 column layout

- every grid consists of:
  + a Container
    + a Row
      + one or more column classes

```
   ex:
      <div class="container">
        <div class="row">
          <div class="col-xx-yy">

   xx => xs, sm, md, lg

   yy => 0..12

```

- classes propagate from small to large
- if you don't specify nothing for large, then whatever you specify for
  medium will propagate for large

- on viewports ***md*** and ***lg*** there is an option for pull and push

  + ***col--xx-yy*** -> move `yy` number of columns to the ***right***
  + ***col--xx-yy*** -> move `yy` number columns to the ***left***

  + ***hidden-xx*** -> content will only be hidden on the **xx** screen size
    (make this visible on every viewport except for the one, we're mentioning here)

  + ***visible-xx*** -> content will only be visible on the **xx** screen size
    (hide something, unless i'm on certain screen size)

  + ***sr-only*** -> content is hidden on all devices except screen readers    


### notes

- bootstrap is mobile first, larger screens inherit values from smaller screens










