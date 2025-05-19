# Specificity Calculate 

a = Number of ID
b = Number of classes, pseudo classes, attributes
c = Number of elements, pseufo elements

To calculate the specificity number, we have to write this order

a, b, c


h1{
  color:red;
}

*a=0, b=0, c=1 == 1*


.heading{
  color:blue;
}

*a=0, b=1, c=0 == 10*


#heading{
  color:green;
}

*a=1, b=0, c=0 == 100*


div > #heading{
  color: black;
}

*a=1, b=0, c=1 == 101*


##### Note:
Universal Selector (*) = 0
Element, Pseudo Element = 1
Class, Pseudo Class, Attribute = 10
ID = 100
Inline CSS = 1000
!important = 10000