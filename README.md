## Moved to GitLab

**Warning**: This project has been moved to GitLab: https://gitlab.com/balping/snake-prizm

----

# Snake for CASIO PRIZM calculators

	version: 1.02
	Developed by balping@cemetech.net
	e-mail: balping.official@gmail.com
	license: GPLv3
	© balping 2013-2014
	original package downloadable at http://ceme.tech/DL885
	help and support: via e-mail (balping.official@gmail.com) or at Cemetech forum: https://www.cemetech.net/forum/viewtopic.php?t=9870

## Instructions

Feed the snake by controlling its head to the right direction, to eat the food, to get it grown. Avoid blocks and the tail of the snake. Enjoy this classic computer (calculator) game!

![screenshot 1](https://www.cemetech.net/img/ss/001630.gif)
![screenshot 2](https://www.cemetech.net/img/ss/001631.gif)

## Controls

* Press `[F1]` to display the help.
* Press `[F2]` to launch the setup menu.
* Press `[MENU]` or `[EXIT]` to return to the main menu and pause the game.
* Default control with the arrow keys, but you can modify it under the keyboard setup menu.
* After continuing the game press any control key to start the game.

## Setup

**Wait**: duration in milliseconds. For example if it's set to 500, the snake moves one block in every half seconds.<br>
**Keyboard setup**: you can change here the controls. Press the keys that you want to use in the gameplay. Keycodes and usable keys are displayed in `keyboard.png`<br>
You can restore the default settings by pressing Default.

![keyboard.png](https://i.imgur.com/PFy0m2u.png)

## Levels

There are 6 built-in levels, these are originally made by Nokia. Future releases will support custom levels and will contain a built-in level editor.

## High scores

Each level has a separate high score page, you can reset them one by one by pressing `[F5]`.

## Files

This game saves three files to the main memory. You can find these in `Memory Manager/Main Memory/@SNAKE`

These files are:
* GAME: contains your current gameplay. If you delete it, you won't be able to continue your paused game.
* HIGHSCR: contains your high scores. Delete this if you want to reset the high scores.
* SETTINGS: contains your settings. If you delete it, your settings are restored to default.

## Upgrading

If you upgrade from v1.00 or from v1.01 your high scores and your current gameplay will be lost.

## Changelog

	v1.00 2013.04.11.
		First release
	v1.01 2013.04.24.
		Icon added
	v1.02 2013.12.28.
		5 new levels added
		The high scores table changed
