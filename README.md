# Jumping Jack ![jumper](/assets/images/jumper.png)

**Table of Contents**

1. [About](#about)

2. [How does it work?](#how-does-it-work)

3. [Technologies Used](#technologies-used)

4. [Demo](#demo)

5. [Installation](#installation)

6. [Contributing](#contributing)

8. [License](#license)

## About
Jumping Jack is a game developed in JAVA, using JAVA Swing and AWT packages for a window-based GUI. 
The rules of the game are simple. The central character, Jack, is trapped in a castle on fire and has to jump over walls in order to escape.
The movement of Jack is very similar to that of birds in the popular game, Flappy Birds.

## How does it work?
The window-based GUI is created with the help of the JAVA Swing and AWT packages.
On startup, a menu is displayed which begins a new game upon a mouse click.
The game creates new instances of both the jumper and the walls it must jump over.
The gaps between walls are randomly generated and if the jumper hits any of the walls, he dies.
An appropriate death message is displayed.

## Technologies Used
* JAVA
* JAVA Swings 
* JAVA AWT (Application Window Toolkit)

## Demo
Here are a few screenshots of the game in action!

* **Say hello to Jack, our jumper!**

![Jack](/assets/images/jumper.png)

* **This is the startup screen of our game**

![Startup](/assets/images/start.png)

## Installation
1. Clone or download the repo from [here](https://github.com/deepikanaryani/JumpingJack.git)
2. Replace the path of the .jpeg files [here](/app/Wall.java), [here](/app/Jumper.java) and [here](/app/Game.java)
3. Run [Main.java](/app/Main.java)

## Contributing
Feel free to contribute to this repo. For contribution guidelines, please read [CONTRIBUTING.md](/CONTRIBUTING.md)

## License
Jumping Jack is licensed under Apache 2.0 License. Please see [LICENSE](/LICENSE) for more information.


