# Seeker

CSE210, Week 8 team group assignment, Greed


# Greed
Greed is a game in which the player seeks to gather as many falling gems as possible. The game continues as long as the player wants more!
Dozens of rocks and gems will be falling from above. Try to catch as make gems as possible to get points, but beware of the rocks. You will lose twice as many points if you get hit by a rock. You can move left, right and up or down in limited range.

#Rules
Greed is played according to the following rules.

Gems (*) and rocks (o) randomly appear and fall from the top of the screen.
The player (#) can move left or right along the bottom of the screen.
If the player touches a gem they earn a point.
If the player touches a rock they lose a point.
Gems and rocks are removed when the player touches them.
The game continues until the player closes the window.


## Getting Started
---
Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.

```
python3 -m pip install raylib

```
After you've installed the required libraries, open a terminal and browse to the project's root folder. Start the program by running the following command.

```
python3 greed

```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the 
project folder. Select the main module inside the hunter folder and click the "run" icon.


## Project Structure
---
The project files and folders are organized as follows:
```
root                   	         (project root folder)
  +--__main__.py		             (program entry point)
  +--README.md			             (general info)
  +--game/
    +--casting/
      +--actor.py                (game class with methods)
      +--cast.py                 (game class with methods)
      +--gem.py                  (game class with methods)
      +--rock.py                 (game class with methods)
    +--directing/
      +--director.py             (game class with methods)
    +--services/
      +--keyboard-services.py    (game class with methods)
      +--video-services.py       (game class with methods)
    +--shared/
      +--color.py                (game class with methods)
      +--point.py                (game class with methods)


```

## Required Technologies
---
* Python 3.10.1
* raylib

## Author
---
---
* [Kevin Cross Minchakpu](kevinomics101@gmail.com) 

