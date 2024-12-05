
# Pokemon Battle Sim (python)
This is a text based Pokemon battling simulator, as obvious as that is by now. This program takes elements from both the mainline games and the trading card game, so it ends up being its own thing, in a way.

Fight with various trainers. If you're up for the challenge, take on the 8 gym leaders and meet with the champion. 


## FAQ

#### How many Pokemon are there?

[number], I plan on adding more whenever I get the time

#### Where's the Elite 4?

I cannot be bothered to add them right now, maybe in the future.


## Authors

- Cleo C


## For the code lurkers
You're curious and snooping through the code, but since I'm not actually that good at coding you may be like "what the hell am I looking at?" I'll explain it here the best I can.

#### [ battlesim.py ]
This is where everything comes together to create the giant, awful mess that it currently is. The variables are self explanatory, besides the "setPlayerName" function.  
"Why do we need that? createLog() already sets your name" Well, due to my lack of knowledge on how to make this work the way I want it to, without that function, if you wanted to change your name for whatever reason you'd have to reset the *entire* log, wins and all. It basically exists so that doesn't happen, which is also why createLog() immediately becomes useless after you first start up the program (unless you delete the logfile).

((more to be added))

#### • [ trainers.py ]
this exists to keep data on all the trainers. Their pokemon, dialogues, whether they're gym leaders or not, etc.

#### • [ pkmn.json + moves.json]
This JSON file keeps the info on all the pokemon and moves in the program.

#### • [ pkmn.py + moves.py ]
The sole purpose of these is to transfer the data from the JSON files to Python so they can be imported to Battlesim. There's probably an easier way to do this. But whatever.

#### • [ dialogue.json ]
Makes it to where the pixels on your screen can say stuff. Aren't they cute?
