# Space Chopper


[Play it here!](https://sheriffhoodie.github.io/space-chopper/)

![Gameplay Gif](assets/images/space-chopper.gif)

### Background & Instructions

Space Chopper is a 2D side-scrolling spinoff version of the classic Helicopter arcade game for one player involving keeping a constantly falling helicopter hovering and dodging oncoming obstacles that appear randomly. The player simply uses the "F" key to fly the chopper: pressing and holding down will cause the helicopter to steadily ascend while lightly tapping at regular intervals will keep it hovering at the same altitude and letting it go will cause the helicopter to lose altitude.

There is no "end" to the game, your distance is tracked as you fly forward and is given to you as your score when you crash the chopper into an obstacle or the top or bottom edges of the screen. Once the game is over after a crash, users can restart the game with the Enter key.

### Features

In the game, users can:

* start, pause, and reset the game screen
* fully control the altitude of the helicopter as described above and guide it through the maze of floating obstacles
* see their score updating in real time, and presented to them at the end
* view the high score, stored locally
* experience a gradual difficulty increase based on score, via increase of the interval and velocity of the oncoming obstacles
* enjoy sound effects and background music during the menu and gameplay with a mute button option


### Architecture and Technologies

The game uses vanilla JavaScript with HTML, CSS, and HTML Canvas for rendering with HTML5 Audio for sound effects and background music interface / playback. The game's functionality is categorically split into separate files OOP-style, e.g. Rock.js, Chopper.js, Sounds.js, etc., for easy navigation and organization. In addition, the game employs the ES6 Singleton module for caching images and sprites and the obstacle images are preloaded as a head script to avoid loading delays.

### Future Directions

* Save global high scores to a database with a username, display top 5 high scores before game start and after game end
* Create different difficulty modes (easy and hard) that the user can choose from before play
* Create playlist of shorter tracks that rotate through automatically
* Add moving/rotating sprites for obstacles

### Credits

* Music: 'Heliscope' by Jesse James,
       'OuterSpace HipHop Beat' by Cyrov Instrumental,
       'Twilight' by DJ Aphrodite
* Explosion Sound Effect: https://opengameart.org/content/big-explosion
* Explosion Sprite: https://opengameart.org/content/explosion
