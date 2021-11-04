# TIC-TAC-TOE game development using TurboC graphics

This is a mini project (Tic-Tac-Toe game) for Turbo C / C++ Compiler.

## Background

Hello, gamer! This is my 1st-semester project for graduation level that was developed in the Turbo C/C++ graphics. I would like to share my project with the game world…:)

## Introduction

TIC-TAC-TOE is the most popular and easiest game. It is a two players(X and O) game, where each takes turns marking the spaces in a 3×3 grid. I was developed is game in the TurboC graphics with interfacing keyboard event and also shown some interactive animation. This article will be helpful for anyone who wants to develop this type of game using TurboC graphics. So let’s get started…

## Requirement
To run and develop TurboC graphics code, you need the following,
* Firstly, you need to TurboC compiler to execute and run the code. 
* Secondly, graphic mode functions require a graphics monitor (at least 640x480) and adapter cards such as CGA, EGA, and VGA.
* Thirdly, to start graphics programming then you need two files which are GRAPHICS.H and GRAPHICS.LIB. These files are provided as part of the TurboC compiler.

## Download & Install TurboC
You can download the TurboC++ for window 7 or 8 in 64bit from the following link:-
[TurboC++ for Windows!](https://www.softpedia.com/get/Programming/Coding-languages-Compilers/TurboCplusplus-for-Windows-7.shtml)

After downloading and installing the TurboC++ compiler, you can automatically find the related header file GRAPHICS.H And for the GRAPHICS.LIB file can be found in the following path:-
```
C:\TurboC++\Disk\TurboC3\LIB
```

It need not set by you when you run a code. Only you need to set the initgraph() 3rd variable path is as follows:-
```
initgraph(&gd, &gm, "c:\\turboc3\\bgi " );
```
N.B: Consider that your TurboC++ compiler installed in the C:\\ TurboC++ \
Now put the code \TurboC++\Disk\TurboC3\BIN folder and now open the TurboC++ Editor. Go to File>Open and browser the path of TIC_TAC_TOE.CPP and open the file.


## Introduction Animation
![Introduction Animation](https://raw.githubusercontent.com/bdstar/TIC-TAC-TOE-Game-Graphics-TurboC/main/image/1_IntroductionAnimation.png)

## Menu Options
![Menu Options](https://raw.githubusercontent.com/bdstar/TIC-TAC-TOE-Game-Graphics-TurboC/main/image/2_MenuOptions.png)

## Choose Start Game
![Choose Start Game](https://raw.githubusercontent.com/bdstar/TIC-TAC-TOE-Game-Graphics-TurboC/main/image/3_ChooseStartGame.png)

## Enter Player Name
![Enter Player Name](https://raw.githubusercontent.com/bdstar/TIC-TAC-TOE-Game-Graphics-TurboC/main/image/4_EnterPlayerName.png)

## Blank Box
![Blank Box](https://raw.githubusercontent.com/bdstar/TIC-TAC-TOE-Game-Graphics-TurboC/main/image/5_BlankBox.png)

## Win Match
![Win Match](https://raw.githubusercontent.com/bdstar/TIC-TAC-TOE-Game-Graphics-TurboC/main/image/6_WinMatch.png)

## Draws Match
![Draws Match](https://raw.githubusercontent.com/bdstar/TIC-TAC-TOE-Game-Graphics-TurboC/main/image/7_DrawsMatch.png)

## Wrong Position
![Wrong Position](https://raw.githubusercontent.com/bdstar/TIC-TAC-TOE-Game-Graphics-TurboC/main/image/8_WrongPosition.png)

## Quit Game
![Wrong Position](https://raw.githubusercontent.com/bdstar/TIC-TAC-TOE-Game-Graphics-TurboC/main/image/9_QuitGame.png)

## Conclusion
Tic-Tac-Toe is the most popular game. So download the source code and run it to play the game. Happy Coding…:)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)