# GoTimer
A simple external bomb-timer for CS:GO, written in Python. You will not get vacced using this, because it uses [Valve's public gamestate integration](https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive_Game_State_Integration).

## Demonstration
[![A simple video demo](http://img.youtube.com/vi/tEdAwi1Hqbk/0.jpg)](http://www.youtube.com/watch?v=tEdAwi1Hqbk)

Click image to see a small clip of GoTimer in action.

## How to use
To download the code/program, either press download on the top of this page, or *git clone* the repo.

You need Python 3, download from [here](https://www.python.org/downloads/).

You also need to place the **gamestate_integration_go_timer.cfg** from the **listener folder** in your cfg folder. The path is typically  X:\PATH_TO_STEAM\steamapps\common\Counter-Strike Global Offensive\csgo\cfg .

With these in place, simply launch go_timer.py ("python go_timer.py") and start the game. You can also start the timer after the game has been launched.

To test that it works like it should, you can try planting the bomb in an offline game vs bots, in competitive mode.

**For Windows users, here's a more detailed how-to:**

1. Install python 3.5 (or atleast 3.x). Make sure to check that "Put python in PATH" is enabled.
2. Check that it's working by opening up a cmd and writing python -V. It should print the python version 
3. If you installed it, but writing python -V does not work, it is not in the path. Google "put python in path windows" to fix. 
4. Put the cfg in the listener folder in your own cfg folder 
5. Go to the GoTimer folder and double-click the run_go_timer.bat file. A timer window should appear. 

**For Ubuntu users, here's a more detailed how-to:** 

Credits to [testiclopz](https://www.reddit.com/user/testiclopz) for this how-to. It is assumed that python3 is already installed.

1. In the terminal: sudo apt-get install python3-tk
2. Unzip the folder from github anywhere you want
3. Place the gamestate_integration_go_timer.cfg from the listener folder into your cfg folder. The path is typically ~/.steam/steamapps/common/Counter-Strike Global Offensive/csgo/cfg
4. Use the terminal, and make sure that your current directory is in the unzipped folder
5. Type *python3 go_timer.py* to launch the program

## Credits
The GameState-listener is inspired by [csgo-c4-hue](https://github.com/doobix/csgo-c4-hue).

I also got some valuable tips from the [Quick Start guide to CS:GO Game State Integration](https://github.com/tsuriga/csgo-gsi-qsguide).

Lastly, a shout-out to [Double0negative for being the first (?) to do this](https://github.com/Double0negative/CSGO-HUD).
