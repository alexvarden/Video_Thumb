# Video_Thumb

This method allows the developer to save thumbnails of video files from the client side using javascript. this can then be transported over the network as a png stored as a 64 bit data-url. 

Firstly it takes a frame from the video element and maps it onto a canvas element (which can be hidden by css). From here the canvas can serialise the image as a png stored as a 64 bit data-url. This is a string of characters that can be decoded as a file on the server level.


