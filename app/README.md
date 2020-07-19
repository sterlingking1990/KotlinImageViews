## Working with Images in ImageView

###### Image can be placed to the center of the screen by first setting the layout_width to match parent
###### and then you can decide to scale the layout_height to either 400dp as I have used here.

## Adding Image to the ImageView
###### Then the next step is to add your image into the drawable folder of the res. The res is like where resources used by your app is kept,
###### It also keeps things like icons and takes care of rendering them intelligently according to screen size

###### When you have place your image on the drawable, you can add the src attribute to the ImageView from the code section of the xml
###### Sometimes the image added might not be able to fit to occupy the dp you have specified for the layout_width. In other to work around this,
###### the scaleType is used.

## Working with the scaleType
###### ScaleType can be of different values
1. center
2. centerInside
3. centerCrop
4. fitXY
5. matrix
6. fitStart
7. fitEnd
8. fitCenter

## center
###### When you choose the scaleType of center, it will place the image to the center of the container or ImageView. if the iamge does not occupy the 
###### size of the dp you choose, the image is placed to the center, and it could make the image appear smaller since it doesnt occupy the intended space

## centerInside
###### working with centerinside will make the image to be positioned inside as though its been zoomed out from the center of the ImageView
###### this further makes the image appear smaller

## centerCrop
###### centerCrop scaleType is usually the preferred if you are looking at getting the dimension to adjust in height and width to fit the scale of the image
###### it does not distort the images origin quality

## fitXY
###### this will scale the image to stretch to the X axis and Y axis of the dimension fo the ImageView

## matrix
###### this will position the image within a row/col scale of the dimension. i.e it first makes a row col grid of the dimension and then places the image in the first row first col of the matrix

## fitStart 
###### thwis will fit the image to the top of the dimension. usually the top

## fitEmd
###### this will fit the image to the end of the dimension. usually the bottom

## fitCenter
###### this will fit the image to the center, it works like center Inside as well

