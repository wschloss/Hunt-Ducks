Walter Schlosser
Eric Koerlin
Ben Fuller

CSCI445 Team Project 1 - Duck Hunt
------------------------------------------

To fulfill this projects requirements, we decided to implement
the classic Nintendo game Duck Hunt. Duck Hunt turned out to be
a great choice since it was easy to translate to a click based
game, which allowed us to focus on implementation instead of
deciding how it would be played.

The CSS3 features we used included:
-An animation for the dog walking under the game canvas
-A linear gradient for the page's background
-A 3D transform on the walking dog image so he turns around at
	the page edges
-Border radius on the canvas and title
-Box shadow on the canvas and title

In addition to these features, we created an about and credits
section at the bottom of the page which the navigation bar can
also jump to.  We also styled the navigation bar links so that
the page has a visually appealing theme as a whole.

While implementing the game in Javascript, it was nice to enjoy
the features of a high level language such as dynamic typing.
The ducks were implemented as Javascript objects with positions
and targets, and it was easy to manipulate these traits.  The 
ducks were stored in an array which was easy to manage since
the function splice(index,amount) can easily remove objects.

We used the Javascript function setInterval(function, time)
which schedules the specified function to run every specified
interval in milliseconds.  This was exactly what was needed for
our game logic function which managed the change of duck 
positions and game state from title to play to game over.  It
was also convenient since it didn't interfere with the mouse
click listener which was attached to the canvas to allow the 
player to shoot ducks.

In the end, the game was implemented in an efficient manner by 
taking advantage of Javascript and HTML5.  We also made the
page appealing to the player with some useful CSS3 features.