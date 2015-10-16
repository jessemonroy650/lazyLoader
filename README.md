## README ##
Date: 2015-03-13

*lazyLoader.js* is intended for loading javascript files and images, after the HTML page loads. It is the simplest of implementations. More sophisticated loaders can be found on this reference matrix by ''http://eric.daspet.name/ , @edasfr or @webperf_fr'' 

[List of Lazy Loaders](https://docs.google.com/spreadsheet/ccc?key=0Aqln2akPWiMIdERkY3J2OXdOUVJDTkNSQ2ZsV3hoWVE#gid=2)

I created this simple function because I just needed the simplest functionallity. I found a good source a stackoverflow; the link is in the code.

### How it works ###
The test page (included) has examples for both.

- `lazyLoader('carrot.jpg', 'img', 'content', 'img0')`;
 - 'carrot.jpg' is the image to load
 - 'img' is the type to load, literally the HTML element type
 - 'content' is the load point in the document, the 'id' of a <div> on the test page
 - 'img0' is the 'id' for the image

- `lazyLoader('alert.js', 'script')`;
 - 'alert.js' is the name of the script file to load, in this case in the same directory.
 - 'script' is the type to load, literally the HTML element type

NOTE: The alert.js launch an `alert("hello");` after 3 seconds, and the writes `console.log("hello");`

If you are confused, look at the code (1096 byte, 93 word, 43 lines -  with comments)
