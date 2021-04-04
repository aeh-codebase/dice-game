# Dice Game 21 For PHP

This project is a simple web application with front controller for testing Object Oriented Programming, SESSION and MVC in PHP.

[Features]
- This web app has no any database.
- All data like game setting, history will be saved in SESSION.
- Namespace and autoloader
    "autoload": {
        "psr-4": {
            "Mos\\": "src/",
            "Webprogramming\\": "src/"
        },
        "files": [
            "src/functions.php"
        ]
    },
- Classes
-- Dice
--- You must be able to hit / throw / roll the dice.
--- You should be able to pick up the latest battle.
--- It must be configurable how many sides the dice have.

-- GraphicalDice
--- It can also have a graphic representation that shows a dice.
--- This dice should have 6 sides.

-- DiceHand
--- You can configure the object how many dice it should contain.
--- You can roll all the dice at once.
--- You can retrieve the values ​​of the rolled dice.

[Rules]
- You can choose whether you want to play with one or two dice.
- You can choose whether you want to play with text or graphical dice.
- You roll the dice and get a result. Then you can throw again to get more points. You should get as close to 21 as possible.
- When the player is satisfied, it can "stop".
- If the player gets 21, note a big "Congratulations!".
- If the player gets over 21, then he has lost.
- Then it's the computer's turn. The computer wins by an equal points.
- If the computer gets over 21, you won this round.
- As a pure premium, you can bet "bitcoins" in each game round. The player can start with 10 bitcoins and you can bet a maximum of 50% of your bitcoins per game. The computer can have 100 bitcoins when you start.
- The bet amount will be selected the amount less than between the player and computer.
