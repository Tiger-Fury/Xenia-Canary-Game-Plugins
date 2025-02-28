<h1 align="center">Viper Re-ignited Multi-Game Xbox 360 Trainer</h1>

Hello this is a my revamped Xbox 360 (RGH/Jtag) "Viper" Multi-Game Trainer which i ended suppport for in 2015, 10 years on and now we have the greatness which is xenia. 

I have started developing this again "Viper Re-ignited" this is to support not only xenia emulator but also an RGH/Jtag.
## Update

I have been told by several people that sometimes the Hashes don't match there games so going forward, I will only be proving a template for the plugin.toml file that you need to edit in Notepad and add your own hash

## RGH/Jtag

On a RGH/Jtag it will be the usual load the trainer.xex by opening the Trainer_loader.xex and this will load it into memory

## Xenia canary
Currently I'm providing patches for the games and versions i use, you may have to get your own hashs from the xenia.log file.
Xenia Handles plugin patches this way so until Global Plugins are added, then the trainer.xex must have a plugins.toml file beside it per game and/or per title update basis. These Patches must be in its own title id folder within the main plugin so the structure currently is like this 

* Xenia/plugins/Yourgametitleid/plugins.toml

and the Trainer.xex must also be in the same folder as the plugins.toml file.


## Trainers

My Trainers scan and adjust there own code which eliminates the need for you to have 
* matching media id
* specific Title updates. 

the only requirements is having  

* Matching Title ID (rare but a few games have different title id's like gears 2)
* Xenia Canary [build](https://github.com/xenia-canary/xenia-canary/releases) from 1st January 2025 onwards (Supports Passcode UI)
* Your matching hash code (Found in xenia log after launching your game and closing xenia look for "Module Hash:" in the log)

currently my trainers use Passcode ui but i'm likely going to change this to keyboard ui instead to make it easier for users of xenia.

## Usage

place the plugins in the correct folders (structure shown above) and once in game you can activate the Trainer by press Dpad up + Back Button or alternatively you can use Dpad up + start button. 
If you are using xenia it will display a list of codes you can activate and use the drop down menu to correspond with the correct keys to active the cheats you want. On Xbox (RGH/Jtag) when the menu appear input the code Dpad Down x 4 to list all codes available.

## How will you know if the trainer is loaded?

Once the Trainer has loaded into memory a Notification will pop up saying "Viper Re-ignited Trainer Loaded" on Xbox this help pop up immediately after loading the trainer, on xenia this will happen when you load the game. If you have a Matching Title ID that is supported by this Trainer then another notication will pop up when you load the game has loaded displaying the titles name.

## How often will i update this?

I will update this whenever I can, I also have a full time job and run a YouTube Channel so updates will come here and there
