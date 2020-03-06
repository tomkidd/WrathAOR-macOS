#  WRATH: Aeon of Ruin for macOS with Xcode project

This is a port of the of the game [WRATH: Aeon of Ruin](http://www.wrath.game/) based on [the source release](https://github.com/KillPixelGames/wrath-darkplaces) from KillPixel Games to macOS. 

![menu screen](https://raw.githubusercontent.com/tomkidd/WrathAOR-macOS/master/wrath_menu.png)

As of this writing, WRATH is only available on Windows, and although KillPixel plans to port it to macOS and other platforms, I thought I'd take a swing at getting it running on macOS from their provided source code. Since it is based on [DarkPlaces](https://icculus.org/twilight/darkplaces/), the odds of it compiling on macOS was high.

Effectively this repo should be the same thing as building the SDL version of the official repo with a Makefile, except I decided to put it in an Xcode project for ease of editing, debugging, etc. 

Anyone wanting the latest code should refer to the official repo, especially once the official macOS port is out.

What works:

*  Runs in macOS
*  Sound effects
*  Input, etc.

Known issues

*  Crash in the first real level, something about cubemaps `¯\_(ツ)_/¯`
*  Fullscreen with DarkPlaces is not working. May be related to age of DP snapshot? (2014)

![gameplay](https://raw.githubusercontent.com/tomkidd/WrathAOR-macOS/master/wrath2.png)