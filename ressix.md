## bootstrap navigation

- decide what type of links u want:
  + nav-tabs
  + nav-pills

```
  ex:

    <ul class="nav nav-tabs">
     <li role="presentation" class="active">
      <a href="#">Home</a>
     </li>
     <li role="presentation">
      <a href="#">Profile</a>
     </li>
     <li role="presentation">
      <a href="#">Messages</a>
     </li>
    </ul>
```
<hr/>
<br/>

- decide on layout (horizontal, stack, justified, etc)


```
  ex: of nav-stacked

    <ul class="nav nav-tabs nav-stacked">
     <li role="presentation" class="active">
      <a href="#">Home</a>
     </li>
     <li role="presentation">
      <a href="#">Profile</a>
     </li>
     <li role="presentation">
      <a href="#">Messages</a>
     </li>
    </ul>

```
```
  ex: of nav-justified 

    <ul class="nav nav-tabs nav-justified">
     <li role="presentation" class="active">
      <a href="#">Home</a>
     </li>
     <li role="presentation">
      <a href="#">Profile</a>
     </li>
     <li role="presentation">
      <a href="#">Messages</a>
     </li>
    </ul>

 notes:

- when u resize the window, nav-justified, changes to nav-stacked   
- by default bootstrap is going to spread tabs evenly

```

### drop downs

- to add dropdown menus you need to include the ***bootstrap js*** files
  and a link to the ***jQuery***


```
  ex: of drop down 

     <ul class="nav nav-pills">
       <li>
        <a href="#">Regular link</a>
       </li>
       <li>
        <a href="#">Regular link</a>
       </li>
       <li role="presentation" class="dropdown">
        <a class="dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-hashpopup="true" aria-expanded="true">
        Dropdown<span class="caret"></span>
        </a>
          <ul class="dropdown-menu">
            <li>
             <a href="#">Option One</a>
            </li>
            <li>
             <a href="#">Option Two</a>
            </li>
            <li>
             <a href="#">Option Three</a>
            </li>
          </ul> 
       </li>
     </ul>

```  

### navbar class

- the navbar class serves as a navigation header for your application  or site.
- navbar positioning:
  + navbar-static-top
  + navbar-fixed-top
  + navbar-fixed-bottom



```
 ex: navbar-static-top
     
 <nav class="navbar navbar-default navbar-static-top">
  <div class="container"
     <ul class="nav nav-pills">
       <li>
        <a href="#">Regular link</a>
       </li>
       <li>
        <a href="#">Regular link</a>
       </li>
       <li role="presentation" class="dropdown">
        <a class="dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-hashpopup="true" aria-expanded="true">
        Dropdown<span class="caret"></span>
        </a>
          <ul class="dropdown-menu">
            <li>
             <a href="#">Option One</a>
            </li>
            <li>
             <a href="#">Option Two</a>
            </li>
            <li>
             <a href="#">Option Three</a>
            </li>
          </ul> 
       </li>
     </ul>
  </div>
 </nav>    


```

> note: using a `nav` class does not convey semantics
> ARIA attribute => role="navigation"





















































