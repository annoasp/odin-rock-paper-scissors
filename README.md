My attempt at the Rock Paper Scissors project in The Odin Project.

Step 1 - Initialise

I've initialised the git repo and created two starting files, this readme and the index file with a script tag directly within it.


Step 2 - Understanding and then planning the project

I've added comments about the project into my index file, just so I don't need to switch windows so often and also to make sure I do understand what the instructions are asking for.

I'm then going to split the work up into the 5 sections suggested, computer's choice, human's choice, score variables, playing a single round, playing the entire game.

It does seem relatively simple, but I'll still make a point of adding the pseudocode first each time to try and build the habit at this early stage.


Step 3 - Computer's choice

I initially thought to try and convert Math.random's output to integers, but no need really. I just set the range boundaries on the if statements to less than 0.333 for rock,  greater or equal to 0.333 and less than 0.666 for paper, and greater than 0.666 for scissors. Testing using console logs show it to be working okay.

I had also thought to include an alert message to show "Computer chose X" alongside the returns, just so the user is aware of it and it's not all happening in the background. That seems like a step that is better included in the logic for playing a round however.

