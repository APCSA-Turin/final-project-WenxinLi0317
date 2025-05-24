
1. Project Overview - Nothing Can Go Wrong

This is a narrative game on a web browser. It uses Unsplash's API to pull images that are implemented in the web page to help players better experience the game, and will show different endings based on the player's choices. It checks whether the user has reached a certain node (knots in Ink), and if true, it will display the corresponding text.

2. Code Breakdown

downloadUnsplashImage(keyword, filename)
	-ask Unsplash for a random photo matching the keyword
	-see if there is errors for API requests
`-get the image url
-download and save the image as given filename
downloadAll()
	-defines an array of objects with keyword and filename
-Loops through each item
-calling downloadUnsplashImage() for downloading

var savePoint
loadSavePoint()
	-check save state
    -return true if exist then load it into ink
restart()
	-clear all display content
	-update savepoint to new initial state
	-re-display the story from beginning

3. Features Implemented 
 - Uses an external API (Unsplash API)
 - Uses multiple Javascript methods and logic
    -async, event handling, state management
 - Provides interactive user experience via web GUI and dynamic image display 
 -Save/load data
 -Use a javascript framework and build a web based front end application 
 -use keyword as content filter when filtering Unsplash images

4. Output Example

See output.gif under WalkthroughHere

5. What I Learned
how to connect to a public API in Javascript
how to build an interactive web GUI
how to build an interactive web GUI that can handle event
some insight of javascript and scripting language Ink

