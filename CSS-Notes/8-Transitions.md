# Transitions

 - transition
 - transition-delay
 - transition-duration
 - transition-property
 - transition-timing-function



 #### transition-property & transition-duration

 div{
  width:100px;
  transition: width 4s;
 }

 div:hover{
  width:200px 
 }


 #### transition-timing-function

 *The transition-timing-function property can have the following values:*

 - ease
 - linear
 - ease-in
 - ease-out
 - ease-in-out

 #### transition-delay

 div{
  transition-delay: 1s;
 }

 ## shortand

 div{
  transition: transition-property transition-duration transition-timing-function transition-delay;
 }

 div{
  transition: width 2s linear 1s;
 }