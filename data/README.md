# Cosmic Cavern

## Mayhem
The manager file consists of a game of Mayhem, a space-themed game where two players navigate a cave/planet/forest while trying to shoot each other down. The ships need to refuel, and avoid hazards such as other planets, bats or birds. Players earn points by shooting opponents and loose some if they perish. The scores and wins of each round are tallied up. May the best space pilot win!

All the images, sounds and other environmental variables are contained in the config file.
This implementation is based from our solution to the third obligatory assignment in INF-1400: Objektorientert Programmering. The addition of start/end/game screen, customisation and music/sound effects (which are currently not working) are done by Tora K. Homme.

### Authors
Tora K. Homme

Dulmini S. Gamage 

## Installing pygame
Ensure that python is installed

```bash
  python --version
```

Ensure that PIP is installed

```bash
  pip --version
```

Install pygame 

```bash
  pip install pygame
```

## Run the game
Go to src directory

```bash
  cd CosmicAdventure/src 
```

Run simulation

```bash
  python3 manager.py
```

## Key Commands
- Start Screen
    - ```press "SPACE"```
    - ```to start game you first need to pick ships and arena```
        - ```press 1 for arena, and switch between the arenas using < >, and press "SPACE" to confirm```
        - ```press 2 for first ship, and switch between the colours using < >, and press "SPACE" to confirm```
        - ```press 3 for first ship, and switch between the colours using < >, and press "SPACE" to confirm```
     - ```press "SPACE" when ready```

- Player 1
  - ```to thrust, press "W"```
  - ```to move left, press "A"```
  - ```to move right, press "D"```
  - ```to shoot, press "LEFT SHIFT"```

- Player 2
  - ```to thrust, press "ARROW UP"```
  - ```to move left, press "ARROW LEFT"```
  - ```to move right, press "ARROW RIGHT"```
  - ```to shoot, press "RIGHT CTRL"```

- End Screen
    - ```to restart game, press "SPACE"```
    - ```to customize arena and/or any of the ships, press "g"```
    - ```to exit ther game, and see the credits, press "ESC" ```

## Features
- Gravity 🕳
- Ships loose fuel in motion, but can refuel 🚀
- Scary, evil alien 👽
- Scoreboards 📊
- Start/game/end screen ⏱

## Currently not working as pygame mixer will not initialize😭
- Music 🎵
- Crash sound and effect 💥
