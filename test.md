# **CSS CHEAT SHEET**

## **Adding Fonts**
```
body{
      font-family: "Lato",sans-serif;
      font-weight: 400;
      font-size: 16px;
  }
 ```
add it to the body so it will inherit to all the other elements inside body
*some parameters like padding is not going to inherit*

*{
Universal Selector applies to every element
}

box-sizing:property allows us to include the padding and border in an element's total width and height.


Include Font details in the body because it is going to inherent

height: vh means the percentage of viewport hieght ex: 95vh means 95% view port height
background-size: cover; this will fi the element in the viewport
background-image: linear-gradient(to right bottom,#7ed56fcb,#28b485b2),url(../img/hero.jpg); This set the gradient to bottom right corner

padding is not get inherited
