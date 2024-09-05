# HelloBulletsHell
I want bullets, lots of bullets... and even more!

During a two-week coding jam on the Quest 2 with Vincent, working on his space game, I began writing code using Unity's Job System to handle a massive number of bullets.

Since then, I've been fascinated by videos of starship battles filled with countless projectiles. It inspired me to create a game with that same chaotic energy.

Managing a huge number of bullets is both a challenge for the game and for the player. If you're developing such a game to learn coding, it becomes an even greater challenge for a beginner developer.

Thus, **Hello Bullets Hell** is not just a workshop to create a game, but also a learning experience that covers:
- How to use Unity3D's Job System
- How to leverage Compute Shaders
- How to implement binary compression for networking

I hope you enjoy it and look forward to playing our game once it's released!

If you have a video of a space game, movie, or anything else with lots of bullets,  
feel free to share it with us by creating an issue :)  
https://github.com/EloiStree/HelloBulletsHell/issues



My goal is to create a massive multiplayer game in a single lobby, supporting thousands of players. To achieve this at a "low cost" on the server, I have a few potential solutions:

- Players will only interact using integer-based commands.
- Players will have a limited bandwidth for information requests (beyond what's necessary for bullet management).
- The bullet engine will only handle the creation and destruction of bullets over the network.
- Paying players can host a broadcaster, allowing them to play in groups of 5-300 players, from LAN connections to the main server.
- It's up to AI or custom code to predict player positions based on bullet sources.
- In future versions, we may allow subscription users to play as human characters, utilizing network LOD (Level of Detail) to manage player positions efficiently.
