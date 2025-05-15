# CSS Animations

## Animation Property

 - @keyframes
 - animation-name
 - animation-duration
 - animation-delay
 - animation-iteration-count
 - animation-direction
 - animation-timing-function
 - animation-fill-mode
 - animation


 ### animation-iteration-count

 *The animation-iteration-count property specifies the number of times an animation should run.*

 div{
  animation-iteration-count: 2;
 }

 ### animation-direction

 *The animation-direction property specifies whether an animation should be played forwards, backwards or in alternate cycles.*

 The animation-direction property can have the following values:

 - normal
 - reverse
 - alternate
 - alternate-reverse



### animation-timing-function

*The animation-timing-function property can have the following values:*

- linear
- ease
- ease-in
- ease-out
- ease-in-out


### animation-fill-mode

*The animation-timing-function property can have the following values:*

 - none
 - forwards
 - backwards
 - both


## Animation Shorthand

The example below uses six of the animation properties:

div {
  animation-name: example;
  animation-duration: 5s;
  animation-timing-function: linear;
  animation-delay: 2s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}

To shortand:

div {
  animation: example 5s linear 2s infinite alternate;
}