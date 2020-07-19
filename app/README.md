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


