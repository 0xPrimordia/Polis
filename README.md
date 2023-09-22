<img src="https://0xprimordia.github.io/Polis/assets/logo.png" width="200" />

## Tactical / RPG
Lead your Hoplites across intense RPG/Tactical battles, a detailed event system and epic mythic quests.

With Polis having such a grand scale, development will be split into a series of mini games with a final phase of tying them together. This repo is aimed at our first goal, the battle mini game.

## Deployment
Deploy your characters based on their traits and relationships with adjacent characters. Chose between 2 rows or square formation, deeper columns providing greater defensive bonus and more columns allowing for flanking opportunity at the expense of a thinner line.


<img src="https://0xprimordia.github.io/Polis/assets/deployment-1.png" width="600" />
<img src="https://0xprimordia.github.io/Polis/assets/deployment-2.png" width="400" />

A Hoplite is measured by his <a href="https://en.wikipedia.org/wiki/Arete" target="_blank">Arete</a> which is derived from a base value of talent, training points, ancillaries, morale and fitness (a possible penalty from injury). Certain traits and overall Arete can give advanbtages or disadvantages to certain positions, ie a lower level of Arete will suffer penalties for the frontline position and a veteran might gain bonuses for frontline deployment.

<img src="https://0xprimordia.github.io/Polis/assets/character-card.png" width="600" />

## Battle Turns

Each turn you can pick one character's action. Once that character’s action has been used, he cannot use
an action again until all other character’s currently playable have used their actions. 

## Battle Phases

Through the course of the battle, a fatigue meter will wear down. At certain 
points both sides will pull back allowing a reprieve for adjustments to positions and healing actions.

<img src="https://0xprimordia.github.io/Polis/assets/fatigue.png" width="450" />

At sunset, both sides withdraw and return to the camp to continue the next day. At this point you can 
re-enforce, if you have the reserves available.

<img src="https://0xprimordia.github.io/Polis/assets/sundial.png" width="150" />

## Othismos

If all character’s ability is active (can be used per above) then one can invoke Othismos. You will be prompted to
select an opposing column to attempt to shove back two spaces. Some math we have to finalize will be applied and if 
successful, two of your characters will push into their line. Once invoked, it has a X turn(s) cool down and all your player actions
are skipped for one turn.

## Position and Actions

Available actions depend on the position of the hoplite, each row allowing for certain attacks or special actions (such as "maneuver").

<img src="https://0xprimordia.github.io/Polis/assets/actions.png" />

### Sword Strike

A close range attack only available to frontline units. A d(x) check to cause (y) to the opponent directly in front.

### Spear Strike

A longer rage attack that can target the opposing frontline or center line unit, only available to the center line units.

### Rear Position Abilities

Rear (3rd position) units can swap with the center unit directly in front, left or right of them. They can also be maneuvered
to an empty adjacent position. Lastly, they can throw a javelin (up to x ammunition) as a distance strike at any unit within range.

### Support Abilities

In addition to Rear abilities, support can heal restoring their morale and potentially decreasing any fitness nerfs. Thus you cnn cycle units back from the 
center to recover.

### Frontline Caveats

The frontline is engaged and thus cannot be swapped until there is a reprieve (see battle phases). There is also a check against Arete for frontline units that
effects morale. If a character is already suffering a negative moral, their disposition is compounded. All of these conditions apply to units maneuvered to frontline
during battle as well as their state at deployment.
