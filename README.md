# css-landing-page
Creating a landing page inspired from The Odin Project.
Thanks to The Odin Project

this landing page will cover basics of css and html which i have learned in past couple of weeks.
few basics to some flexbox properties to create a landing page.

working on header. time 09:40 am. April 23
header work finish i think it looks as as it is seen in example file. april 23 10:47

working on hero section. time 14:44, April 23
will use min-height on hero so it can grow more than the height specified if theres more content to it
but it won't get smaller than min-height.
also using flex: 1 on child containers of hero section to get 2 container of eqal width.

working on info section. time 17:24 april 23.
going to create a info section using semantic element article which represents stand alone info parts of a webpage.

also ill look for adding a hover effect on link items in navbar.

work on info section almost done. time 8:19 april 24.
there was an issue on image divs of info section as i had to choose between how to keep them at reasonable size
and for that i had two options. using fixed width and height at image div or using flex: 1 auto 
flex: 1 auto didn't work so i used fixed width and height at image div.

images edges were getting overflowed from their respective container so used height width to % values, hidden the overflow of image and also used object-fit property though it didn't have effect since images were not overflowing exactly but staying on rounded edges of its container, so also used border radius 12px on image. slightly lower than the container.

working on quote section of page. 
it is a container that wraps two p elements and contained in a section element with max-width set to 1000px margin set 0 auto for center aligning the quote container inside quote section.
the quote section will have min-height set to 400px as well so the size gets increased if the content gets larger.

Call to action section - time 20:26 april 24.

completed this section so far. what i learned is by default items of flex container are stretched to fill the container. when we use properties like justify-content or align-items then it will make the child dimensions(width and height) equal to its content. 
this is what i saw through practice. it also written everywhere but now i have noticed it.

so if i want any flex child to have dimension equal to its flex container i can use stretch property which is by default, if there's any content inside flex-item of flex-container which needs to have height equal to its flex-container which is child of main flex-container. there are several ways. 1. align-item: stretch. display: block and height 100%., also i can use flex: 1 on flex-item of main flex-container so it will be fill be filled up based on flex-direction 
its like if flex:1 fills the container based on the flex-direction then align-items: stretch property will allow the item to stretch in perpendicular side. 
just wanted the link Sign up inline anchor element to stretch take height equal to its sibling container and it is acheived through align-items:stretch property.
slightly kept the quote block smaller than the quote container.
# Images copyright.
1. image1 - Photo by Mariah Krafft on Unsplash
2. image2 - Photo by Parsa Mahmoudi on Unsplash
3. image 3 - Photo by ruedi häberli on Unsplash
4. image 4 - Photo by Samuel Quek on Unsplash

# Quote Taken from
Goodreads.com [Steve Jobs quote](https://www.goodreads.com/author/show/5255891.Steve_Jobs)