This is to test the save and load functions of the program while it is in WebGL format.

There is a save and load feature that stores the data in the browser's cache files.

Unity WebGL doesn't support accessing the computer's files because of browser privacy.
This also causes an issue where you are not able to copy things from the game into something out of the game and you can't paste something into the game form out of it. 
I found a user-made plugin though that solves the copy and paste issue. Here is a link to it: https://github.com/Trisibo/unity-webgl-copy-and-paste

There is also an option to save a string of text which outputs the JSON file data. This also the user to store that data locally. It is also easy to change some numbers in the JSON data to change what is stored.
With that JSON string, it can be loaded in the other input box.
