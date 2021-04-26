# ai-wolf-GT
AIWolf General Info

Gabby Orr
Travis Mewborne

Accessing Our Java Class Files
The most recent upload of our java files that we created can be found in the “ai-wolf-GT” folder. The files that we modified are located in src/org/aiwolf/gt
Our primary focus was on the seer (GTSeer.java) agent.
The files we wrote ourselves are listed below:
QLearningAgent.java
GTState.java
qTable2.txt
The files we modified to use our AI are listed below:
GTSeer.java
GTBasePlayer.java


Running AIWolf
This project requires at least Java 11
We have condensed and compiled our project into a jar file, called “GTWolf.jar”
This jar file is already in the “AIWolf-ver0.6.0” folder, so you don’t need to compile anything.
The folder also requires a “qTable2.txt” file, which is already in there.
Download “AIWolf-ver0.6.0”
Navigate to the folder from terminal and run using the following command:
For mac/linux: “sh AutoStarter.sh”
For windows, run AutoStarter.bat (I don’t know how to run .bat files).
Executing AIWolf runs the game ten times. The final 6 output lines indicate the number of games won for each AI for each role. For example, the number of wins 
the gtAgent has is in the 4th column. The fraction represents (number of games won)/(total number of games played as the given agent). Note that we only implement
the Seer agent and run the game with GTWolf in the Seer role.


Customizing the Run File
You can edit “AutoStarter.ini” to change the number of players and the number of games played.
To edit the number of games to simulate, change the value of “game” on line 4. The default is 10.
To change the number of players, copy and paste (and rename) the samples as needed. The game requires exactly 5 or 15 players. The number of players does affect the win rate.
Note that changing the number of players can affect the “qTable2.txt” data. To reset the qTable, remove “qTable2.txt” from the directory, duplicate “qTable.txt,” and rename it “qTable2.txt”
Our agent only has SEER implemented, and there can only be one seer per game. Therefore, there should only be one agent using our code, and that agent should be assigned to SEER (already done).
