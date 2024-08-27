# Core Hunt
A high-fidelity game prototype for MITxPro's Game Design Course.

## Description
This is a digital board game in which your objective is to find and destroy your opponent's cores before they destroy yours. The game takes place on a 10x10 board, and players have access to information gathering and obfuscating tools, such as scanning and core moving. Additionally, placeable walls contribute a huge part to the strategic complexity and uniqueness of the game.

The code is presented above is not the true source code, but rather a transpiled version of the true source code, which is a very large and illegible mass of generated JSON code from the platform used. It was made using a tool I created just for this assignment (which I then shared with the community at large) to make the code legible. All of the code can be viewed in bulk in the main `full_code.df` file.

## Platform
This game was, as was approved (and encouraged) through my 1:1 capstone project video meeting with Rodrigo, made entirely on a game development platform aimed at making games in Minecraft, called DiamondFire. As such, to play this game, you will require a copy of Minecraft: Java Edition.

As such, I am assuming some basic familiarity with how Minecraft's control scheme works.
If mostly unfamiliar with custom Minecraft servers, there are a few paradigms that are important to note.

1. Right-Clicking while holding items is the typical way to use or activate them.
2. Commands are prefixed with `/` characters and must be typed directly into the chat box, which is typically opened with `T`. On this platform specifically, there is also a secondary type of command that starts with `@` instead.
3. Items may have important descriptions that show up when you hover over them in your inventory.

One small thing of note is that the credits will not list my real name. This is because this is a community I am a huge part of where many people know me and I would prefer to keep my privacy. My username is "Electrosolt" and that is the name used in the credits.

## Where to Play
To play this game, you will need to join the server `mcdiamondfire.com` on Minecraft: Java Edition. From there, you will need to do the following:
1. Type `/join 140344` to open the game.
2. Type `/chat dnd` to hide external chat.
3. Type `@emeritus`. This will the the password used to enter the game. I am using a password as to not publicly share the game just yet. 
4. Press the number keys on the keyboard to pick options in the menu. Presumably, press [4] to read the "How to Play" section, then press [1] to play versus the AI. If you are testing this game with multiple people, press [2] instead to join the multiplayer queue.
5. You will now be put into a match.

## Important Information
There are some important things to note regarding commands you can take and possible game-breaking bugs in the system.
- If you wish to stop the game, you may type `/play` to return to the main menu, or `/s` to leave altogether (after which you will have to type `/join 140344` again).
- If the game crashes, it will not be visible, but rather the code will simply cease to work. This is a preventative measure on the server's side which I unfortunately have no control over, designed to prevent malicious actors from lagging the server. It shouldn't trigger during a normal playthrough, but if this happens at random, you may reboot the game with `/play`.