# myhero
Easy plug-in to create headers

## Get Started
First, you need to add the myhero Css Js file and Jquery in your project:
```
<!-- Myhero css -->
<link rel="stylesheet" href="css/myhero.min.css">
...
<!-- Myhero js & Jquery -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script src="js/myhero.min.js"></script>
```

Now you need to add the class my hero to your html element, for example:
```
<header class="myhero"></header>
```
## How to use ?
You can use different class to stylize your elements:
### Data you can use
 - To use your image as a background, you need to add data-src="<*Link to your image*>" to your element, for example:
```
 <header data-src="img/bg.jpg"></header>
```
 - To use a color as background, add data-color="<*Your favorite color*>":
 ```
<header data-color="crimson"></header>
 ```
 - You can use en other color to make a gradiant to do this you need to add a new data, data-gradient-color="<*Your second favorite color*>":
  ```
 <header data-gradient-color="yellowgreen"></header>
  ```
 - By default the gradient direction is right if you want to change it, add data-color="<*direction*>":
   ```
  <header data-gradient-direction="left"></header>
   ```
   - To change the size of your element you use two datas, add data-height="<*Your height*> and/or data-width="<*Your width*>":
     ```
    <header data-height="100%" data-width="100%"></header>
     ```
### Class you can use
 - To display your image as cover, add the class cover to your element:
 ```
 <header class="myhero cover"></header>
 ```
 - Make the image not repeat it self, add the class no-repeat:
 ```
 <header class="myhero no-repeat"></header>
 ```
 - Your can use different class to justify your image:
    1. center
    1. top
    1. right
    1. left
    1. bottom
    1. top-right
    1. top-left
    1. bottom-right
    1. bottom-left
```
<header class="myhero top-right"></header>
```
- Make the image not repeat it self, add the class no-repeat:
```
<header class="myhero no-repeat"></header>
```
