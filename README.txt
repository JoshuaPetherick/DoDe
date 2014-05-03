
The Destruction of Deimos

 Contents:

	Story...
	How to Run...
	Objective...
	Known bugs and issues...


 The Story

	Within our system lurks a planet, not far from our homeland. We call it Haven, but it used to 
	be known by another name. Mars. Alongside this planet is one of our first space	base, from the days 
	where we crawled forward towards our galaxy. 
	
	We hadn't recieved many reports from this small encampment, and only a few hours ago did we learn why. 
	A flaming ball of destruction, commonly known as a meteor, has collided and shattered the moon of 
	Deimos. Our men on that station have sent us an emergeny SOS, requesting any help that we could 
	provide them.

	Which is where you come in. We're sending you out to save as many of our fellow men out on that planet
	and bring them home to their wives and children. Whenever you're ready, climb aboard MY beautiful ship,
	and go make a name for yourself, captain!


 How to Run

	I have created an executable file called "finalgame" which you can use to run the final version
	of the game. If you wish to complile or create a new executable then you open up the terminal, cd to 
	the DoD folder and then type in:

		"g++ -c -std=c++11 src/*.cpp -I /usr/include/sigc++-2.0/" &
		"g++ -o finalgame *.o -lSDL -lSDL_image"	&
		"./finalgame"

	This is how you run it within a linux terminal.
	
	All of the images are saved within the assets folder, you will see the images used within a game and 
	images that I used for testing them. You can see the difference in detail, and read from the names,
	of the files, the different versions.

	All of my coding pages are found within the src folder, and some other coding pages can be found within
	 the other folder named "Files.o" as all of the files with .o were safely placed in here.

	If you find yourself curious about the development of the game then I have also attached some sketches
	from before I begun coding it, and even kept the different tests from each day I coded within the test 
	folder. There should be 7 in total, with 1 being the very start of the game development, and 7 being
	the most recent.


 Objective

	As the story suggests, the objective of the game is to save as many Astronaughts as you can. You
	also have to try and dodge some fiery bits of meteor debris as it flaming well shoots towards you (try
	not to have your wing clipped). Luckily your ship is also equipped with some pretty powerful weaponry,
	so try use it frequently. Some of our more local satallietes around the area have also been seen flying
	about, so you'd do well to avoid (or use) them if possible.

	Use the arrow keys to move around the screen and press the spacebar to shoot. 

	The game comes with a score, which will be printed to the terminal at the end of the game. You earn 1 
	point for destroying a meteor and 50 points for saving a fellow Astronaught. The satallites will not
	only push your north, towards the meteors, but will also destory any meteors that it collides with. It
	is useful to remember that.


Known bugs and issues

	-	Excessive use of firing will slow the FPS down, and may even crash the game
	-	Bounding box is wide on the character, due to wings, and meteors can hit an invisible area
		at the front of the character.
	-	Colliding with the satallites from the back will push the player in front of them.
	-	Random generate 'sometimes' causes them to randomly generate e.g. such as the first appearance 
		of the meteors.
