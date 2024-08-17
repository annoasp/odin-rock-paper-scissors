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


Step 4 - Human's choice

I initially thought to use some kind of check variable to run the while loop, but it worked the same with just true as the condition.

I also initially had an if statement, two else ifs and then an else, to capture the 3 desired inputs and then a catch-all for any that we don't want. But it seemed simpler with checks for rock paper and scissors all in one if statement, and then an alert that they need to pick a correct input in the else.

For the returns I also opted to return a lowercase string since it will save adding any extra steps in later functions. But it's easy enough to strip out that string method and just return the user's input directly if that makes more sense at a later stage.

Testing shows it to be working as I'm expecting so far.


Step 5 - Playing a single round

I tried not to overthink this part too much, so some simple branching if/else statements, with the basic case being if the human's choice and the computer's choice both match, as that will lead to a draw and no gain in score.

It did occur that it might look a bit cleaner with an initial if to see if the choices match, and then a switch statement underneath the else with three cases listed ( covering rock, paper, scissors), each having a ternary operator to decide between the possible outcomes (computer wins, computer loses).

I've stepped through playing rounds trying to cover every case and the winning statements and scoring variables all seem to be working as intended.