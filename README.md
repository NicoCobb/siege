# siege
A deck-building strategy board game with influences of fire emblem, dominion, and yu-gi-oh

# rules
__players__: 2

## Unit
<img src="https://github.com/NicoCobb/siege/blob/797e6cf8d2c71e31732041b7e3fed4109f3c2efb/Sample_card.png" height="400" />

1. A unit's card will have an image of a marker that corresponds to this unit. These markers are what will be placed on the board when a unit is played.
2. Certain cards will have ability text. This will be listed underneath the marker image.
3. Every unit has a color value. This will be noted by a colored border on the card. 
   1. Units can be __red, green, blue, or neutral__.
   2. Each color is __effective against__ another color, with the exception of neutral.
      1. __Red__ beats __Green__
      2. __Green__ beats __Blue__
      3. __Blue__ beats __Red__
      4. __Neutral__ is __equal to__ all other colors.
4. Every unit has a cost on it. This will be displayed above where the unit's marker is on the card.
   1. 0-cost units will __have no value__ displayed on the card.
   2. A unit's marker will have as many stars on it as it's cost is equal to.
    

## Drafting
1. A coin is flipped to decide who begins drafting first. The same player will make the first move of the game.
2. ##Each player starts by picking a leader for their team. 
3. 15 cards are drafted from the given selection. Players alternate in the selection process.

## Setup
1. Once drafting has finished, players may place 4 starting units __of their choice__ under these restrictions:
   1. The first unit placed must be your leader. __Leaders are placed on top of your siege tower__. 
   2. Units can be placed on any space within a __2-space wide__ radius around the siege tower. 
   3. Players alternate placing units. The player who will be starting places a unit down first. 
   4. Once each player has **4 units down** setup is complete.
  
## Turns
1. __Draw__: Players decide if they would like to either
   1. Draw up to __five cards__ for their turn.
   2. Draw up to __four cards__ _and_ __draft an additional card__ and __shuffle it__ into your deck.
      1. Drafting also means a player has __one less summoning point__ for this turn.
2. __Summon__: _(see summoning section for specifics)_
3. __Move__: up to 5 of your units. Each unit's move amount will be listed on the card.
   1. Units __CANNOT MOVE ONTO MOUNTAINS.__
4. __Attack__: with up to 5 of your units. These do not necessarily need to be the same units who were moved. _(see attack section for specifics)_

## Summoning
1. ##Units will have a cost on them. This is how many units must be sacrificed to summon this unit.
   1. A 0-cost unit requires no sacrifice, a 1-cost unit requires 1 sacrifice, ... an n-cost unit requires n sacrifices.
2. Players have 4 summoning points per turn. Summoning a unit will use 1 more point than it's listed cost.
   1. For example, a player could summon 4 0-cost units on one turn, or 2 0-cost and a 1-cost.
  
## Attack
1. When a unit attacks, the attacking player rolls the number of dice blocks that corresponds to their attack value.
   1. If a player rolls a __4, 5, or 6__ the attack is a __hit__.
   2. If a player rolls a __1, 2, or 3__ the attack is a __miss__.
2. If the attacked unit is not dead, and if the attacked unit __is in range__ to attack back, the attacked unit will counterattack in the same manner.
3. __Modifiers__
   1. If a unit has color advantage when it attacks, it gains __1 additional attack point__.
      1. Consequently, if a unit has color disadvantage when it attacks, it __loses 1 attack point__.
   2. __Terrain__ may also impact a unit's attack.
      1. If a unit attacks a __covered__ unit (a unit who is on a __forest__ space), the attacker must roll a __5, or a 6__ to land a __hit__.

## Win Condition
1. The goal is to be the first player to make it to __20 victory points__.
2. Victory points are earned by spending a turn with a unit on top of a tower.
   1. The two towers _in the center_ are worth __1 point__ per turn.
   2. The _enemy tower_ is worth __10 points__ per turn.

