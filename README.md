#Describe your work process

##What will be your initial approach to the task?

My initial idea was to use a responsive grid. After evaluating the mosaic it did not fit any grid system that I was aware of. To better understand the layout I copied the mock-up into Adobe illustrator to mark out the boxes and layout guidelines. I marked the relative dimensions of each element. After this I tried to lay everything out with floats but realized this could not be done. I then succombed to positioning all elements absolutely. With this approach I had to layout each element one by one. As the layout shown in the mock-up is supposed to be static this approach is okay but not very flexible. The dimensions for all elements are defined as percentages to allow the layout to scale fluidly. A basic javascript event handler is provided to activate the modal and (slowly but surely) navigate the images in the gallery.

##Did you use any external libraries?

No.

##Is there any other way you could fulfill this assignment?

Yes. There are frameworks to support mosaic layouts like masonry. There are other more javascript heavy approaches to acheive a more flexible layout. 

##If so, why did you use this method?

I kept to CSS and HTML to demonstrate that it could be done.

##Tell us about one challenge you had and how did you overcome it?

There were several challenges but the most salient was trying to maintain the aspect ratio of the image containing elements when the viewport scaled. It's not as easy as applying a height to the element in a percentage value. To overcome this challenge I consulted various tech blogs and Q and A forums such as stack overflow. I also asked a friend for some advice at points. The following along with a lot of experimentation with the layout allowed me to get through it.
