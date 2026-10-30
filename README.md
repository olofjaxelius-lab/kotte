# Bomberman World — [your game title]

**Student:** Olof Jaxelius

## How to play

- **Controls:** Move around with WASD, place bombs with SPACE, reset with R
- **Objective and rules:** You win the game by destroying all of the enemies, if both happens at the same time ***
- **Configurations / demo setup:** defult

## Features and validation

| Feature | Check, observed result, and expected behaviour |
| --- | --- |
| 1. Player damage and death | I tested that the player took damage when hit by both enemies and bomb blast. The player took the right amount of damage and it was as expected. |
| 2. Round states and objective | I tested the roundstates by both dying and winning the game. It switched the state and paused all the playing round features as expected. |
| 3. Safe restart | I tested to die and the restet the game. By first it didn't reset the enemies which didn't was expected but it was fixed. |
| 4. Solid bombs with owner escape | I tested by placing a bomb and moving away from it and try to walk on top of it again and wasn't able to as expected. |
| 5. Blast-range pickup | I tested by looking that the powerup spawned and applied when picked up. It was able to be picked up and applied as expected. |
| 6. Multible bombs per owner | I tested it by placing the bomb limit and it wouldn't place Another one until one of the bombs had exploded. |
| 7. Shield or temporary invulnerability | I tested it by picking it up and trying to take damage by both bomb blast and the enemies and no damage were taken. |
| 8. Chain reactions | I tested it by placing bombs with a gap so it would hit each other and when the first exploded the other did so too. |


**Known issues:** None known after testing

## Sources and assistance

This project builds on the shared Kotte foundations.

I have used github copilot for help on insperation of how to do different tasks and help for when it didn't work but I wrote the code myself and came up with how to write it myself.


