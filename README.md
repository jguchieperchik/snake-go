# Snake [![](https://godoc.org/github.com/nathany/looper?status.svg)](https://godoc.org/github.com/tristangoossens/snake-go/game) [![Go Report Card](https://goreportcard.com/badge/github.com/tristangoossens/snake-go)](https://goreportcard.com/report/github.com/tristangoossens/snake-go) [![Build Status](https://travis-ci.com/tristangoossens/snake-go.svg?branch=master)](https://travis-ci.com/tristangoossens/snake-go)

This is a Terminal based snake game made by tristangoossens. The game is built by using the [termloop](https://github.com/JoelOtter/termloop) engine.

## The game

Here is a GIF of the first version of the game!

![alt text](https://github.com/tristangoossens/snake-go/blob/master/images/game-v1.gif "Version 1")

## Game settings

Here is a demo on how the game settings panel works. for more information on this [click here](https://github.com/tristangoossens/snake-go/blob/master/docs/gameoptions.md).

![alt text](https://github.com/tristangoossens/snake-go/blob/master/images/gameoptions.gif "Game options")

## Save score

**IMPORTANT!**    
You need to clone the repository in order to use this function, for more information [click here](https://github.com/tristangoossens/snake-go/blob/master/docs/instructions.md).

![alt text](https://github.com/tristangoossens/snake-go/blob/master/images/savehighscore.gif "Save highscore")

## How to play

First of all you will need Go, you can find more information [here](https://golang.org/).

When you have installed Go, you will need to install the game:

```shell
go get github.com/tristangoossens/snake-go
```

Then play it using the following command:

```shell
$GOPATH/bin/snake-go
```

## Bucket list for future versions

- [x] Implementation of the skull mechanic
- [x] Implement game difficulty options: easy, normal, hard
- [x] Add a setting panel for a user to change the color of the snake, food and border
- [x] Implement a restart button / quit button on gameoverscreen
- [x] Add score to Gameover screen
- [x] Add instructions to the sidepanel
- [ ] Let user adjust arena size and snake speed(flags?)
- [ ] (could)Add function to check terminal size and adjust accordingly
- [x] (could)Make a local database to save highscores. (markdown file)


