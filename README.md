# Cursor-following-images-effect
This a nice effect that I made using an awarded website as inspiration.
Fairly, simple, first create 10 images in html.
Change their width to 25vw so they are responsive and position them absolutely.
Set their data-index from 0-9 and their data-status to inactive on the start.
Inactive images have a display of none and active a display of block.
Initiallise the images array at the start of the code and the globalIdx of the images is set to 0, and last is an object that will track the x and y coordinates of the last image that was shown.
The create the active function, which will position the image where the mouse is and set it's z-index to be on top.
It will also set the data-status to active and chage the x and y on the last object.
We want images to show only when our mouse travels a certain distance and that why we use the distanceFromLast function which calculates exactly that.
The last handleOnMove function which has an if statement looking has our mouse passed the window.innerWidth / 20 distance.
If it has we say which image we want to show next and use % to get it back to the first one after the last one.
The tail is just used so there are no more than 5 images on screen.
We activate the lead image and set the tail to inactive.
On the last we say that on mouse movement call the function handleOnMove and on mouse touch movement stop and when it's released call the function

If you think anything could be improved let me know!
Thx!
