# Transforms

 - The transform property comes in two different settings, 
two-dimensional and three-dimensional. Each of these come with their own individual properties and values. 

### Transform Syntax#transform-syntax :

 - The actual syntax for the transform property is quite simple, including the transform property followed by the value.
 The value specifies the transform type followed by a specific amount inside parentheses.

          div {
           -webkit-transform: scale(1.5);
            -moz-transform: scale(1.5);
             -o-transform: scale(1.5);
               transform: scale(1.5);

## 2D Transforms :

- 2D Rotate : The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees.

- 2D Scale :  Using the scale value within the transform property allows you to change the appeared size of an element.

- 2D Translate :  The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.

- 2D Skew :  The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.

### Combining Transforms
 - To combine transforms, list the transform values within the transform property one after the other without the use of commas.

       .box-1 {
         transform: rotate(25deg) scale(.75);
         }
        .box-2 {
        transform: skew(10deg, 20deg) translateX(20px);

### Transform Origin 
- The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.

### Perspective

- In order for three-dimensional transforms to work the elements need a perspective from which to transform. The perspective for each element can be thought of as a vanishing point, similar to that which can be seen in three-dimensional drawings.

### Perspective Depth Value

- The perspective value can be set as none or a length measurement. The none value turns off any perspective, while the length value will set the depth of the perspective. The higher the value, the further away the perspective appears, thus creating a fairly low intensity perspective and a small three-dimensional change. The lower the value the closer the perspective appears, thus creating a high intensity perspective and a large three-dimensional change.

### Perspective Origin

- As with setting a transform-origin you can also set a perspective-origin. The same values used for the transform-origin property may also be used with the perspective-origin property, and maintain the same relationship to the element. The large difference between the two falls where the origin of a transform determines the coordinates used to calculate the change of a transform, while the origin of a perspective identifies the coordinates of the vanishing point of a transform.

## 3D Transforms

- Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes, however there is another axis along which we can transform elements. Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.

### 3D Rotate 

- With three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values, including rotateX, rotateY, and rotateZ.

### 3D Scale 

- By using the scaleZ three-dimensional transform elements may be scaled on the z axis. This isn’t extremely exciting when no other three-dimensional transforms are in place, as there is nothing in particular to scale.

### 3D Translate

- Elements may also be translated on the z axis using the translateZ value. A negative value here will push an element further away on the z axis, resulting in a smaller element. Using a positive value will pull an element closer on the z axis, resulting in a larger element.

### 3D Skew

- Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale. Elements may be skewed on the x and y axis, then transformed three-dimensionally as wished, but they cannot be skewed on the z axis.

refrence : 
 - https://learn.shayhowe.com/advanced-html-css/css-transforms/

 - https://learn.shayhowe.com/advanced-html-css/transitions-animations/

 - https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users

 - https://codepen.io/retyui/pen/ByoaXV

 - https://codepen.io/akshaychauhan/pen/oAfae

 - https://codepen.io/kieranfivestars/pen/MYdQxX

 - https://codepen.io/dp_lewis/pen/gCfBv
