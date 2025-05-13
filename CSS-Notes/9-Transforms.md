# Transforms

## CSS 2D Transforms

 - translate()
 - [rotate() - 3D](https://www.w3schools.com/css/css3_3dtransforms.asp)
 - scale()
 - skew()
 - matrix()


### translate() Function

It moves the element's postion in left, right, bottom, top

div:hover{
  transform: translate(40px, 60px);
}


### rotate() Function


*rotateX is top to bottom*

div:hover{
  transform: rotateX(-15deg);
}

*rotateY is left to right*

div:hover{
  transform: rotateY(-15deg);
}

*rotateZ is Normal Rotate*

div:hover{
  transform: rotateZ(-15deg);
}

Note: rotateZ & rotate both are same


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


