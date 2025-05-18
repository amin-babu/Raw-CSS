# CSS FlexBox

 - Main Axis = Left to Right = X Axis
 - Cross Axis = Top to Bottom = Y Axis
 - When we will set {display:flex} in a parent element, every child elements will be in main axis

## Flexbox Container Property

 1. flex-direction
 2. flex-wrap
 3. flex-flow - shothand
 4. justify-content
 5. align-items
 6. align-content



 ### 1. flex-direction 


  *flex-direction's values*

  1.1 = {flex-direction: row;} - by default Main Axis - left to right
  1.2 = {flex-direction: row-reverse} - right to left
  1.3 = {flex-direction: column} - Axis will be changed - (Main axis = top to bottom, Cross Axis = Left to right. It will be top to bottom) 
  1.4 = {flex-direction: column-reverse} - (Main Axix is Top to Bottom, and It will be bottom to top)

 ### 2. flex-wrap
 
 *flex-wrap's values*

  2.1 = {flex-wrap: nowrap;} = By Default = Nothing will heppend
  2.1 = {flex-wrap: wrap;} = will wrap in next line by right-top to left-bottom - (Main Axis)
  2.3 = {flex-wrap: wrap-reverse;} = it will star from bottom & will wrap right-bottom to left-top in top line (Main axis)
  2.4 = {flex-wrap: wrap;} in Column (Main axis - top to bottom) = It will wrap from bottom-left to top-right
  2.5 = {flex-wrap: wrap-reverse;} in Column (Main axis - top to bottom) = It will wrap from bottom-right to top-left
 





 ### 3. flex-flow - shorthand

 *flex-direction + flex-wrap = flex-flow*

  - {flex-flow: flex-direction flex-wrap}
  - {flex-flow: row wrap-reverse;}





 ### 4. justify-content

  *This property aligns all the child content in main axis by left, center, right*

  *Justify-content's values*

  4.1 = {justify-content: flex-start;} = its default value and start from left to right as main axis
  4.2 = {justify-content: flex-end;} = it will start from right to left as main axis
  4.3 = {justify-content: center;} = every child elements will be centered as main axis
  4.4 = {justify-content: space-around;} = space will be every child's element around equaly
  4.5 = {justify-content: space-evenly;} = space will be every child's element equaly in main axis
  4.6 = {justify-content: space-between;} = space will be 2 child's element between




 ### 5. align-items

  *align-items property works as cross axis. It also works as item like a line*

  *align-items's values*

  5.1 - {align-items: stretch} = it will stretch every item if the height is not set
  5.2 - {align-items: flex-start} = every items will be at the top in the line. It follows cross axis
  5.3 - {align-items: flex-end} = every items will be at the bottom in the line. It follows cross axis
  5.4 - {align-items: center} = every items will be at the center in the line. It follows cross axis
 
 ### 6. align-content

   *align-content property as like as  justify-content. The difference is justify-content works as main axis and align-content works cross axis. everything is same*










## Flexbox Items Property

  *Flexbox Items properties are concern about the order, width, and height of child elements*
  
  1. order
  2. flex-grow
  3. flex-shrink
  4. flex-basis
  5. flex - shorthand

  ## 1. Order
    
    *order property's default valus is 0*

    - Lowest valus's element will the fisrt item of the container
    - Biggest valus's element will be the last item of the container

    .one{
      order: 1; //it will be fist 
    }

    .two{
      order: 5; //it will be last
    } 
  
  ## 2. flex-grow

    *flex-grow property distribute the remaining space equaly to fullfill the row*

    - flex-grow default value is 0
    - when we set 1 as value, it distributes the remaining spaces to fulfill the row
    - it increases the fixed width to remove the remaining spacecs to fullfill the row

  ## 3. flex-shrink

    *flex-shrink property is the opposite of flex-grow*

    *it dicreases the fixed width to fullfill the row*

    *But flex-shrink default value is 1. which is why it decreases the item's width to fullfill the row.  When we set flex-shrink:0 it will follow the fixed value*

    *To check the example of flex-shrik - may be I have to use nowrap*

    div{
      flex-shrink:0;
    }

  
  ## 4. flex-basis

    - flex-basis is kind of width and min-width
    - but min-width doesn't decrease the with case its fixed
    - flex-basis can decrease the width if necessary

  ## 5. flex - shorthand

    - flex: flex-grow flex-shrink flex-basis;
    - flex: 1 1 200px;


