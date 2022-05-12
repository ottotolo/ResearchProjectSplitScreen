
## Splistscreen
 
 Double or more splited screen render which can be used to show the player two or more scenarios at the same time,
 or to allow more than 1 player to play on the same device.
 
 ### Market Study
 
 The splitscreen feature has been included in many video games since the start of the gaming industry at home. 
 This resource allows more than one player to play the game at the same time on the same console. This was really
 usefull specially in the early 2010's and 2000's when multiplayer online wasn't fully exploited as it is today.
 
 ![image2](https://github.com/ottotolo/ResearchProjectSplitScreen/blob/main/docs/images/Blackout-Call-of-Duty-Black-Ops-4-Split-Screen.jpg)
 
 Nowadays however, even tho it is still added to many mainstream triple A games, it's very rarely used anymore, so
 I would say it is not a priority or even necessary to add this feature to your game.
 
 ### Possible applications
 
 If you are still determined to add a split screen feature to your game because it is focused on co-operative gaming
 or it's just convinient to add it to your game, a really interesting way to give this old feature a fresh touch, would 
 be by implementing a Dynamic SplitScreen.
 
 #### Dynamic Splitcreen
 
 Dynamic splitscreen is a really exciting approach to the same old feature where the line that separates the screen, 
 reacts to the position of the players. Meaning that instead of separating each player in a screen compartiment, the 
 screen line that splits the cameras rotates, and moves each camera around the screen depending on the position of 
 each player in the game. However this type of feature requires a better performing algoriythm or engine.
 
 ![image3](https://github.com/ottotolo/ResearchProjectSplitScreen/blob/main/docs/images/image-13.png)
 
 ### Coding & Logic
 
 First we need to create the screens needed, which will depend on the amount of players that want to participate. This 
 screens will have to be resized accordingly to  the amount of screens rendered.
 
 ![img1](https://github.com/ottotolo/ResearchProjectSplitScreen/blob/main/docs/images/Captura.PNG)
 
 In order for a split screen to work effectively we need to render all camera views in the same for loop. This will 
 allow all screen frame rates to sync. It will prevent bugs and it will prevent the device from having to load the game 
 multiple times.
 
 ![img2]()
 
 The input however doesn’t give that much trouble since any entity including the screen player gets updated in the render
 for loop. Meaning that simple input detection should be able to handle the different players.
 
 ![img3]()
 
 ### Links and references
 
https://en.wikipedia.org/wiki/Split_screen_(video_games)
 
https://github.com/sebheron/Dynamic-Splitscreen

https://www.reddit.com/r/Games/comments/kisulb/dynamic_split_screen_design/

https://www.youtube.com/watch?v=NXaMeKFmhXM

https://www.w3schools.com/howto/howto_css_split_screen.asp
