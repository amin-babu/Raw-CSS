# Transforms

## CSS 2D Transforms

 - translate()
 - rotate()
 - scale()
 - skew()
 - matrix()


### translate() Function

It moves the element's postion in left, right, bottom, top

div:hover{
  transform: translate(40px, 60px);
}


### rotate() Function

div:hover{
  transform: rotate(-15deg);
}

*rotate() function doesn't have x or y axis. It Only rotates by posetive and negative value* 


### scale() Function

It increases or dicreases the size

div:hover{
  transform: scale(2, 0.7);
}


### skewX() Function

div:hover{
  transform: skew(20deg, 20deg);
}


### matrix() Function

*The matrix() function combines all the 2D transform functions into one.*

*The parameters are as follow: matrix(scaleX(), skewY(), skewX(), scaleY(), translateX(), translateY())*

div:hover{
  transform: matrix(1, 0, 0, 2, 40, -50);
}