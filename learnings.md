## flex-direction
Flex box has concept of axis, There is a main axis and a cross axis( which is 
perpendicular to main axis)
1. row - For row main axis runs from left to right and cross axis runs from top to bottom 
2. column - For column main axis runs from top to bottom and cross axis runs from left to right 
3. row-reverse - Main axis runs from right to left and cross, top  to bottom
4. column-reverse - Main axis runs from bottom to top and cross left to right

## flex-wrap
1. no wrap - default, all elements stay on the same row
2. wrap - Elements are wrapped onto new line 
3. wrap-reverse - reverses the cross axis of elements from top-bottom to bottom-top, doesn't affect the flex-direction

## New css properties
width: calc(33.33% - 20px) - used to calculate the width by subtracting the 
said no. of pixels from the desired width.

## flex 
This property can have any number as it's value ( not just 1)
flex: 1, apply on flex-items, takes all the available width and evenly distributes it among all the flex-items.

## order
order is used to defined the order of items in a list of flex-items
by default order is 0
example - .box3 {order: 1}, this will push box3 towards the end 
order can have both positive and negative values.

## Alignment, justify-content(apply on flex-container)
justify-content: flex-start; -> default
justify-content: flex-end;
justify-content: center; 
justify-content: space-between;
justify-content: space-around;

### vertically center 
flex-direction: column;
justify-content: center;