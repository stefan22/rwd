## breakpoints
- sizes that define a layout change/which rules to apply
- most people dont resize their windows
- breakpoints should correspond to 
  + device
  + content

## mobile first
- you shouldn't see breakpoints for small screens
   + no breakpoints for 320px, 360px
   + you already designing for those screens and        
     are part of the default styles
- you should have ***min-width*** instead of ***max-width***


### media queries step 1

- the meta viewport tag tells mobile browser's viewport how to behave

```
   <meta name="viewport" content="width=device-width, inital-scale=1">

   avoid maximum-scale=1

```

### media queries step 2

- use fluid layouts
- if you use breakpoints, some absolute measurements are not unusual
- percentage vs ems
  + ems are measurement for typography.

- paddings and margins when you use percentage are   
  affected by ***width*** not height


### media queries step 3

- including the media queries - fluid layout that is triggered by certain sizes
- design for ***small screen*** and ***work bigger***  


### stylesheets order

> when triggering for ***minimum width*** you wanna have your 
  ***smallest sizes*** first.

```
  ex:

     h1 {
      width:100%;
      background:green;
     }

     @media screen and (min-width:780px) {
      h1 {
       background:yellow;
       width:50%;
      }
     }

     @media screen and (min-width:1024px) {
      h1 {
       background:blue;
       width:25%;
      }

     }


```

> always make sure they work and stay clean by adding one rule and testing it.


### note about media query placement (depends on min-width or max-width)

- if assuming ***min-width***, put the rules on the bottom

- if you're looking at someone's elses code and they're using ***max-width***,
  then put the rules on the top
















