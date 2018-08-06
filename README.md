frontend-nanodegree-arcade-game
===============================

Students should use this [rubric](https://review.udacity.com/#!/projects/2696458597/rubric) for self-checking their submission. Make sure the functions you write are **object-oriented** - either class functions (like Player and Enemy) or class prototype functions such as Enemy.prototype.checkCollisions, and that the keyword 'this' is used appropriately within your class and class prototype functions to refer to the object the function is called upon. Also be sure that the **readme.md** file is updated with your instructions on both how to 1. Run and 2. Play your arcade game.

For detailed instructions on how to get started, check out this [guide](https://docs.google.com/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true).

### Table of Content

- How to run the game
- Dependencies
- Configurations

#### How to run the game

To run the game, first make sure all files are complete,
check the `fileTree.png`, for reference
Open the `Index.html` to run the game, the rules of the game are set by the `initailiser.js` but the default rules are:
 - Hitting the bugs takes your live, if your live hits zero you die
 - To move use the directional buttons
 - The First level has no bug its like a test your movement stage
 - The Amount of bugs increases every 2 Levels
 - The `score` is calculated by `(level * total gems collected)`
 - The total gems collected is calculated by 
   - `(Green Gem * 1) + (Blue Gem * 2) + (Orange Gem * 3)`
   - Hence Green Gem Has a Value of 1 
   - Blue Gem has a Value of 2
   - Orange Gem has a Value of 
 - Clear Level Ten To win the game
 
#### Dependencies
 
 > https://maxcdn.bootstrapcdn.com/font-awesome/4.6.1/css/font-awesome.min.css
 
 The Game runs different codes at different time obviously,
 This is a break down of where what is located.
 
 - The __Timers__ configuration and implementation is done in the `timer_helper.js` file
 - The __Enemies__ are implemented in the `app.js` file
 - The __Player__ is implemented in the `app.js` file
 - The __GEMS__ are implemented in the `gems.js` file
 - The __Lives__ are implemented in the `live.js` file
 - The __score__, __lives__, level info display and handlers are implemented in the `ui.js` file
 - The `helper.js` contains function definition for specific tasks through the game, like `RandomSelect()` that takes in A json object and chooses one of the objects in the json var at random, and the final score screen after the game is over is also in the `helper.js` file, etc 
 - The configurations for the games, `maxLevel`, player lives and other things are defined in the `initiliser.js` file
 
 #### Configurations
 
 The way i make this game is such that all/most of the values the game requires to run are located in the `initiliser.js` file
 So anychanges to,
 	- Live amount on player start
	- Amount of enemies at starting
	- Amount of Gems on screen if they spawn
	- Amount of Lives on screen if they spawn
	etc are configured in this `initiliser.js` file
## A big Thanks For Viewning my project.