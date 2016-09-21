drumminhands_photobooth
=======================

A DIY photo booth using a Raspberry Pi that automatically sends animated gifs to a Tumblr account. Great for events.

Find the full set of instructions here: http://www.drumminhands.com/2014/06/15/raspberry-pi-photo-booth/
This requires:
  - PiCamera -- http://picamera.readthedocs.org/
  - GraphicsMagick -- http://www.graphicsmagick.org/
  - pytumblr -- https://github.com/tumblr/pytumblr
  - 
  
Inteded Changes for this branch:

1) Add party themed images to instruction screens.<p/>
2) <strike>Fix code to only take 4 pictures.  The code take 5 pictures but only displays 4.  I suspect there is a bug in the loop while taking pictures.</strike><p/>
3) <strike>Comment out the GIF creation code or put in a variable to switch this on and off as needed.</strike><p/>
4) <strike>Add code to create a montage image from the 4 images that are created.  Add comment in the #of pictures taken variable to alert a user that the montage expects 4 images.</strike><p/>
5) Include code to use DSLR.<p/>

Parking lot for future enhancements:<p/>
1) Have montage be flexible for however many pictures are being selected.  Maybe give users options 2, 4, and 6 picture montages.<p/>
2) Add variable to switch between piCamera and DSLR input.<p/>
3) Add integration with instagram and option to post montages to instagram.  Also add a variable to use as the hashtag.  Ideally there would be a user input to ask if the montage should be posted to instagram.<p/>
<p/>
<p/>
<p/>
New ideas after using the photobooth @ party.<p/>
1) Make the photobooth fully automated.  Plug in and things are running.  I think the only thing needed for this is to start up the photobooth program automatically. <p/>
2) Explore what it would take to print pictures.  How complicated is it and how complex would it be to have this be unmanned?
3) Explore use of a DSLR or better camera.<p/>
4) Add lights to the booth.  Include a relay so the RPI could turn on the lights when the booth was going to take pictures and also turn them off once all pictures were done being taken.<p/>
5) Can we have multiple cameras for adults and kids?  Have a selector so the adults don't have to sit or duck down to take pictures.<p/>
6) Have a burst mode so the photobooth can take pictures of the event like the pinata.<p/>
7) Have a setup screen where people can enter their instagram information and authorize the photobooth to post all pictures there.<p/>
8) Have a share screen where people can email themselves the pictures they just took.<p/>
9) Have a screen to upload all pictures to oneDrive or download all pictures after the event.<p/>
