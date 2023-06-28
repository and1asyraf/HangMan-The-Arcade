# Hackathon2-CPT113-Group39
## HangMan - The Arcade!

## Table of Contents: 
* [What is this?](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/edit/main/README.md#what-is-this)
* [Features of the Game](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/edit/main/README.md#features-of-the-game)
* [How to play HangMan - The Arcade?](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/edit/main/README.md#how-to-play-hangman---the-arcade)
* [How object-oriented concepts were used to develop our game.](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/edit/main/README.md#how-object-oriented-concepts-were-used-to-develop-our-game)
* [How linked lists/stacks play a role in our game.](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/edit/main/README.md#how-linked-listsstacks-play-a-role-in-our-game)
* [Screenshots of our game](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/edit/main/README.md#screenshots-of-our-game)
* [Game Demonstration Video](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/edit/main/README.md#game-demonstration-video)




### What is this?
This hangman is an open-source re-implementation of our classic childhood game, hangman, as its name suggests.
It is intended to be used as a game similar to arcade games, where you can compete with other players with your high scores.
This project uses no coding from any sources and is in fully C++. Instead, everything is re-implemented from scratch.

### Features of the Game
HangMan - The Arcade is capable of storing your highest score and compare with previous user.
It uses common and flexible libraries such as iostream, fstream, ctime and cstdlib.
It is cross-compatible with most C++ IDEs.
It offers visual-based with monotone colour and no audio game bringing nostalgic environment.

### How to play HangMan - The Arcade?
Before running the program, it should be noted that HangMan - The Arcade requires (-std=c++11) flag to compile properly.
To run the HangMan The Arcade, simply run the executable h and cpp files. Make sure to have the text file ready to fetch random words from the file and make sure to set your directory according to your devices.
When the game runs, enter your name which will be inserted into the scoreboards in another text file.
Guess the word by entering one character at a time until you complete the word or you guess 7 wrong characters.
You can continue the game as long as you want and collect scores as high as you can, so long as you dont get the HangMan.

### How object-oriented concepts were used to develop our game.
OOP programming paradigm by definition, groups objects by information and behaviour, which are just instances of classes.
The classes establish hierarchies and relationships by defining the characteristics and methods of the objects and by being inherited from other classes.
Objects can communicate with one another, alter their state, and take action by sending messages or invoking methods.
OOP is very helpful for our game because it enables the representation of game things like characters, files, and messages as objects with characteristics and behaviours.
It also enables game logic and data to be encapsulated into manageable units that can be reused and extended.

### How linked lists/stacks play a role in our game.
The Linked List we used is to store 2 types of data which is boolean and character. The character is from the word that the player need to guess.
The boolean is named 'Hidden' and are true, until the player guessed the character. Then the 'Hidden' will be changed to false, revealing the character that they guessed.
The Stack are implemented for the use of displaying the HangMan whenever the player guessed a wrong character. The HangMan will be 'pop' 7 times until which the stack is empty. Then, the player loses.

### Screenshots of our game
![Main Menu of the Game.](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/assets/138023630/734e1eb9-1737-4b4f-955a-51f2ec90e69c)
![Exiting the Game.](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/assets/138023630/b3471fe7-84f6-41db-960e-a24e0651951d)
![Game displays the rule.](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/assets/138023630/79f75e94-9ad7-4599-a6ef-ffc394c50ffe)
![Game displays the score.](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/assets/138023630/3a948790-2e00-4cf4-97b1-f330e6761889)
![Guessing attempt in game.](https://github.com/Asyrafdelaghetto/Hackathon2-CPT113-Group39/assets/138023630/eb980ffa-70ff-48e1-b5e5-f42b6ff153b0)


### Game Demonstration Video
Below is the link to our presentation for Hackathon II Assignment.
We talked about how our program works, showed the gameplay of our game and highlights the feature of our game.

* [Click Here!](https://youtu.be/3v7DkxrtP-Y) 
