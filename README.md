# Games_Platforms_and_Hardware_Task_3

**Student Name:** Harry Lehman

**Student ID:** 2407002

For this task I was instructed to develop a 3D platformer game focused on mobile input interactions and detailed profiling. The game must also have a level environment containing textures, animated NPCs and at least one core gameplay mechanic implemented.

<a href="https://ibb.co/xtThMzBr"><img src="https://i.ibb.co/Mx0nRPtJ/Screenshot-2026-10-22-213920.png" alt="Screenshot 2026 10 22 213920" border="0"></a>  
The first game mechanic I implemented was a simple moving platform. I ceated this by adding an interp to movement component to a floating platform mesh. I then assigned two relative positions as the points it would move between, set the duration to move between these points to three seconds, and set the behaviour type to ping pong so it would move back and forth between the two points.

<a href="https://ibb.co/5WWdt4z3"><img src="https://i.ibb.co/gMMGH9X8/Screenshot-2026-10-22-215242.png" alt="Screenshot-2026-10-22-215242" border="0"></a>  
<a href="https://ibb.co/nML6CL6J"><img src="https://i.ibb.co/VYqJmqJ4/Screenshot-2026-10-22-215426.png" alt="Screenshot-2026-10-22-215426" border="0"></a>  
<a href="https://ibb.co/pjcrxhvH"><img src="https://i.ibb.co/hFb1yYRG/Screenshot-2026-10-22-215601.png" alt="Screenshot-2026-10-22-215601" border="0"></a>  
The next game mechanic I implemented was a simple coin collection system. When the player collides with the collision sphere of the coin, the coins variable in the player blueprint is increased by one and the coin actor is destroyed. I also added a blueprint to update the UI text when the player collects a coin to show how many coins the player has.

<a href="https://ibb.co/xSPwwtnG"><img src="https://i.ibb.co/4Z9CCnbM/Screenshot-2026-10-22-221048.png" alt="Screenshot-2026-10-22-221048" border="0"></a>  
After implementing the core game mechanics, my next step was to implement touch-based input controls. Unreal Engine already has a bult in UI for touchscreen controls, so adding this was as simple as adding that UI to the player view in the world blueprint. The left joystick controls player movement, the right joystick controls the camera angle, and the button above the right joystick allows the player to jump.

The final section of this task was to build the game and run it on a physical android device, and then compare the differences in optimisation between the editor/emulator version and the version running on a physical device. However, due to build error with the university PCs and me not having any android devices, I am currently unable to test the game on physical hardware.