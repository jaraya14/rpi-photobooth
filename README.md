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
