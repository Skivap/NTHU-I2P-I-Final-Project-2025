# Enemy Interaction

Score: 3 points

![Alt Text](./Checkpoint2_gifs/Trainer.gif)

- [ ] (0.25 point) If we stand in front of the NPC, a warning sign will appear.
- [ ] (0.25 point) If we press some button when the warning sign appears, switch scene into a battle scene.
- [ ] (2.5 points) Inside a battle scene, create a battle system
    - It's a turn based system
        - In the first turn, player will do action first, 
        - and in the next turn, enemy will do action second.
        - Repeat back to player turn.
    - Starting from player turn, They have 2 different options to interact, where one of them must be attack. (other option can be run away or interact with item)
    - In player turn, they have atleast one action, which one action must be attack.
    - Each attack must reduce HP of opponent, when it reach 0, the opponent will lose (either enemy losing or user losing)