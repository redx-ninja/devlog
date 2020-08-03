# Entry 002 - More Questions than Answers

## Self-Evaluation
Why do we write code? Growing up it just seemed like it was the only control over anything I had. I wasn't learning to code to solve problems,
but instead I was learning to implement systems of control. Essentially I became the master of pixels.
In college I would come to learn Linux, become exposed to systems level programming. Nearly 5 years later I found controlling bits to be interesting.
My job as a Systems Administrator was a good fit in small-2-medium businesses. They needed people that could control their setups so they could focus on code.
Shifting into DevOps was a real mind bender. Instead of just controlling some pre-defined systems, we also had to solve for the system.
Perhaps that experience would have been more fruitful if I spent time defining "controls" that I had and focused on being a master of that. 
Current mental state is just riddled in jade. I feel like I've become jaded in regards to everything.
Perhaps that comes from feeling like I have a rough idea of everything there is.
I generalized in knowledge, nothing has been interesting to persue true mastery in so far. 
My overconfidence in that generalized pool has dwindled, but I feel like I could conquere any mountain.
It's a double edged sword isn't it? Having vast knowledge pools to pull from and try out new hats. 
People that do it are more rare. Complacency is the enemy and perhaps I'm complacent in knowledge now.
Need to spend more time deciding why I code. A motivating or driving force is necessary to feel pressure and neccesity to compete.

# Game Dev Log
No new progress has been made. Tried out some new games. I'm still debating on what to tackle next. 
I should work on the GUI. I have this idea of what it needs to look like. I want it to have a CS Class that acts like an API.

The API could look like this:
```
PlayerUI.SetHealth(float hp_capacity, float hp_current)
PlayerUI.SetEnergy(float energy_capacity, float energy_current)
PlayerUI.Dialog(string name, string message)
PlayerUI.DialogPrompt(string name, string message, string[] options)
```


Did some research and Raycasting is very useful. Using `Raycast` and `RaycastHit`, you can sense things in a line.
The ray starts at a vector3 point and projects out to a vector3 point that is a "stopping" point. 
This can be used for AI's sensing other things. 
Useful for sensing things in front of a game object. 


Could make a bunch of cube guys find and terminate eachother.

Potential small projects:
- AI cube guy royale (it's even been done before, saw it on youtube, could do "see one, do one" technique)
- Give game objects like name tags that move around as they move
- Make a single map quest, key item with fall puzzle, locked door to access.
- complete interact dialog in click2move schema.
- click2move attack an enemy, cycle AI in
- AI patrol path system? Cylce back to AI.


AI seems to be what I need next the more I think about it. We'll see how it goes. 
