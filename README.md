Games portfolio - Joel Carlsson


The Elsworth curse
Summary:
Group projects with two 
programmers, two graphical 
artists, one sound creator, one 
musician and one 
game designer.
Made during a course at
Högskolan i Skövde.

Type of project:
Explore a haunted house
Solve the mystery
Dialogsystem
Enemies that can hear the player
Pick up objects
Inventory
Developed in Unity and C#
Collab using Github
Link to game and trailer:
https://crowded-game-studios.itch.io/the-elsworth-curse

My focus:
Create a dialogue system that is able to be edited from outside of Unity to allow easier collaboration with game writers. Implement UI technical aspects such as scaling the UI based on screen size and updating various elements during gameplay. Implement working quests that both show on the UI and adapt to the situation to guide the player. Keep track of a note system for the player to remind them of their progress so far. Help the group implement various parts to create a cohesive experience.

Difficulties and solutions:
Finding the best way to create a tool that doesn’t require too much time to learn for other people in the group, while at the same time allowing enough customization to make the desired features work. Through various research and experimentation I ended up using a solution based on the Ink package. This separate program could be connected to the Unity Editor while at the same time allowing changes to be made outside of the main editor. This allowed the two writers of the project to write simple dialogue trees and with the help of simple variables they could themselves add triggers for certain stuff to change in the game, such as completing or adding a quest. It also allowed the customization the group agreed was needed for the project such as text effects, and speaker assigning.


Battle ram
Summary
Group project with 4 programmers
and 2 graphical artists. Made during a
course at LBS Göteborg.

Type of project:
A 1v1 arena fighter
Developed in Unity and C#
Got nominated by LBS Göteborg for the
LBS game awards 2021

My focus:
Implement functionality for two players at the same time, implementing UI and the various features for it such as cooldown timers, health bars and score tracking between rounds. Along with creating various abilities for the player such as their ultimate abilities.








Fire simulation
Summary:
Cooperation between two programmers as a final thesis project at Högskolan i Skövde
Type of project:
Eularian fire simulation based on previous research articles. Real time fire that is painted as a separate layer on top of a model. There are several different variables to change the effect of the fire.
Developed in Unity with both C# and shaderlab
Available online at:
https://github.com/Antonhejhejhej/FireSimulation

My focus:
Research previous implementations
Research various types of technical 
solutions
Adjust and put together earlier research
Measure the performance impact of the
shader and how it can be used within the field










Hierarchical state machine
Summary:
Cooperation between two programmers
Deepdive into different AI implementations

Type of project:
First person shooter
Developed in Unity and C#
Focus on enemy ai inspired by the game Halo: Combat Evolved
Based on a GCD talk by programmers that worked on Halo: Combat Evolved, re-engineered a similar solution.
Enemies that are adaptive based on the players play style and the situation at hand.

Can be found at:
https://github.com/Antonhejhejhej/Hierarchical-state-machine-for-Unity

My focus:
Enemies that can find hiding places from the player and regenerate hp.
The navigation and pathfinding of the enemy.
Emotional states of the enemy based on the situation and several factors such as their hp, remaining ammo, that specific enemy types emotional inclination.

Work process:
This project was hugely based on the idea of trying to recreate the adaptable enemies from Halo: Combat Evolved. We based our initial idea of GCD talk about how they designed and implemented their systems. But this didn’t provide any code, but rather design outlines on what the enemies should, and shouldn’t be able to do to achieve the desired feel of the enemies. With this outline we made our own initial sketch of how we could do this for our own enemies. We landed on a solution that uses a hierarchical state machine that chooses it’s states depending on the situation the enemy is in, such as how many allies are nearby, their hp, and what type of enemy it is. But also what type of emotion it was currently in, through calculating the emotion based on the ideas presented in the GDC talk we got a well working system that was designed to be used in future projects we might make as the code was adaptable and made to evolve. 

This kind of workflow of trying to think about how other developers handled a problem made for a very interesting learning experience. We kind of had a clear goal in the beginning and we just had to find our way there. In the end I think we reached a very neat solution that reaches close in our prototype to what the GDC talk mentioned. However this prototype is smaller in scale so we were well aware that several systems might need to be adjusted to adapt to more thing such as vertical environment and the different tools a player might have available. We did however achieve a solid base that could be built upon as long as we kept the core ideas of what the enemy should be capable of.

Re:Chrome:
Summary:
Group project with me as sole programmer, 
1 sound, 1 music, 1 art, 1 writer

Type of project:
2D rpg with several minigames
Each boss has a unique minigame
Dialogue and exploration between bosses
Made in Unity and C#

Trailer at:
https://youtu.be/2cvzLcMWu7E

My focus:
All of the programming
Movement + exploration
Level design
Minigame programming unique for each boss
Sound and music basic implementation with FMOD

Work process:
One of the most feature intensive games i have made yet. It started with making a simple 2D top down movement and a basic tile map to be used for making the levels. But most of the time was spent on the three totally different bosses. A core pillar for this game was that each encounter would work totally differently, the first one is snake, the second is a kind of Undertale like with dodging different attacks as you move in a square, and the last is dodging attacks by moving sideways quickly and attacks coming from above, kind of like in Everhood. All of this was made in around 2.5 months with me as the single programmer. This required lots of testing unlike most projects I have worked on, as many different things could go wrong, from simple flaws in the level design, to the different minigames not being fun or difficult enough. That is not even counting the various bugs that could occur as this was one of my earlier programming projects. But it also made me realize the power that can come from variety in a game, having different mechanics for the player to experience keeps it fresh and also gives me as the developer a bit more room to not make every single mechanic amazing as it doesn’t stay around for too long.




Solo projects:
Procedural level generation and enemy behavior 
Summary: Practice in programming by making a prodcedureky generated 2D level with many rooms and entrances between them. Along with a boss enemy that adapts to the player behavior by using new attacks and movement abilities.

Type of project:
2D top down shooter made in Unity and C#

Work process:
Most of the time was spent on the level generation 
as it was a new field for me at the time. 
Eventually I reached a solution by a kind of worm 
generation that has a max length to create, and then 
loops while picking directions to add rooms. 
When all the rooms were made it then made entrances
to allow the player to move between them while also 
moving the camera to the new room.

The boss part of the project was an expansion of earlier 2D 
enemies I had created, but I wanted this boss to have a focus 
on adapting to the player and depending on the situation use 
varying abilities, such as a charge at distance, a flamethrower 
at closer range and a barrage of bullets at mid range. 
This ended up being pretty fun while also teaching me ways 
to make the boss feel more interactive for the player.


Smaller project: Game feel
Summary: A solo project made in C# and Unity focusing on various types of feedback for the player such as screen shake, controller vibration, and various ways to reward or punish the player for their actions. Some ways I did this way the enemy growing strong when at low HP so the player felt a need to finish them off and dropping pickups to help the player. Various ways to punish or show the player they need to change their strategies was enemies being able to ambush a player that was hiding for too long.
Lessons: This type of focused project helped me learn the impact both rewarding and punishing the player can have. It's all about a fine balance so the player doesn't feel discouraged to experiment, while also rewarding certain play styles that fit the designed play style.

Smaller project: Component based programming
Summary: A solo project focused on teaching me how to make adaptable and combinable systems to create new gameplay scenarios. Made in C# and Unity
Learnings: This project taught me how as a programmer the way I implement a system can help for example game designers create more interesting and varied content in the game. If I split up various behaviours and let them be combined in many different ways, that can allow new types of enemies to be created purely through new combinations of scripts. For example, making enemies flee as an added script, or adding more attack options such as a chase. Keeping this in mind as an option can certainly help depending on the type of game that is being created and can allow experimenting while designing the game. It also taught me how to use the idea of idea + 1. So that a system works with the idea that is planned while also making sure it is adaptable and even situations that aren't planned at the moment can easily be implemented.

