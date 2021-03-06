<h1 align="center">
  Pokémon gen 4 and 5 overlay script
  <br>
</h1>

<h4 align="center">A script so you don't have to update your overlay by hand.</h4>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#download">Download</a> •
  <a href="#credits">Credits</a> •
  <a href="LICENSE.txt">License</a>
</p>

![Demo](https://github.com/The-f6X/Gen4OverlayScript/blob/master/img/Demo.gif)

[![forthebadge](http://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)[![forthebadge](http://forthebadge.com/images/badges/powered-by-electricity.svg)](http://forthebadge.com)

[![Twitch](https://img.shields.io/badge/as%20seen%20on-twitch-6441A4.svg?style=for-the-badge)](http://www.twitch.tv/the_f6x)[![GitHub license](https://img.shields.io/github/license/The-f6X/Gen4OverlayScript.svg?style=for-the-badge)](https://github.com/The-f6X/Gen4OverlayScript/blob/master/LICENSE.txt)

## Key Features

* Autonomous 
  - Quickly see updates to your overlay with no manual input.
* Customizable  
  - Choose what types of images you want and where they go.
* Current health
  - As plain text and as a bar graph.  
* Current level
* Artwork for each team member
  - Supports empty slots and eggs
* Nicknames
  - Coming Soon™


## How To Use

For this script to work, you need to have the following: 
 * [Python 3](https://www.python.org/downloads/)
 * [Open Broadcaster Software](https://obsproject.com/)
 * [DeSmuME](http://desmume.org/)
 * A generation 4 or 5 Pokémon rom



After downloading the most recent version of the script, you should have a folder like this: 
![screenshot](https://i.imgur.com/O1O2kzK.png)

The assets folder needs to be populated with images of all pokemon and named with their national dex number:

![screenshot](https://i.imgur.com/AseSjBr.png)
* Note: You will also need a file for an empty slot (0.png) and for an egg (egg.png)

In DeSmuME, there is the option to add a lua script under tools -> Lua Scripting: 

![screenshot](https://i.imgur.com/39WQaQl.png)

After the script is running in DeSmuME, you then need to run the python script.

```
cd <path to folder>
python Script.py
```

Then over in OBS, you need to add image sources for the the team members and their health bars making sure to point to the files located in the `out/` folder. 

![screenshot](https://i.imgur.com/Qx0zwTF.png)

Then add the text for each team member making sure to point to the text files in `out/`. 

![screenshot](https://i.imgur.com/XuRiQFT.png)

And you're done! Unfortunately it is a lot of images/text to setup. But when you're done it should look something like this: 

![screenshot](https://i.imgur.com/TWnEHUw.png)



## Download


You can [download]() the latest version of the script for Windows since DeSmuME doesn't support Lua scripting on other platforms.

## Credits
 * [Shawn](https://github.com/shawnrc) for taking interest in the projct and developing the hell out of it. 
 * [KazoWar](https://projectpokemon.org/home/forums/topic/30518-4th-and-5th-gen-misc-info-reading-scripts/) for the original Lua script.
 * [MatPlotLib](https://matplotlib.org/index.html) for the health bar code. 
 * [Markdownify](https://github.com/amitmerchant1990/electron-markdownify) for readme formatting.

---

> Twitch [The_f6X](https://www.twitch.tv/the_f6x) &nbsp;&middot;&nbsp;
> GitHub [@The-f6X](https://github.com/The-f6X) &nbsp;&middot;&nbsp;
> Twitter [@The_f6X](https://twitter.com/The_f6X) &nbsp;&middot;&nbsp;
> GitHub [@shawnrc](https://github.com/shawnrc) &nbsp;&middot;&nbsp;
> Twitter [@\_shawnrc](https://twitter.com/_shawnrc)
