# Overview

This addon adds support for drawing shapes on the screen for various (mostly debugging) purposes. 

Currently there's only support for 2D drawing but I'll be extending this as I need it. 
Send me your feature requests and I'll see what I can do.


# Installation

You need to put the contents of this repository into your project's `addons` folder 
(usually a folder called `addons` in the root of your project).

## Via Git

You can install the addon via git by executing:

```
git clone git@github.com:AlmostBearded/GodotDebugDraw.git ADDONS_FOLDER
``` 

## Manually 

The alternative to installing via git would be to simply download a zip file of this repository 
and extract it into your `addons` folder.


## Autoload

The only thing left to do is to add an autoload for the DebugDraw2D script.

Steps:
1. Go to Project > Project Settings
2. Go to the Autoload tab
3. Add the DebugDraw2D script by locating it via it's path and naming it DebugDraw2D

The result should look something like this: ![](https://i.imgur.com/31EuOoz.png)