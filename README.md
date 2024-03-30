# Neslogaia
A simple text rpg game powered by discord bot

## Intro to Neslogaia
Traveling around the world of Neslogaia using the discord bot commands! Visit different towns, battle mobs and collect items.

You start off on the island of Tutorisle. From there make your way to the main island of Neslogaia and explore.

### Player stats
Base stats:

|Stat| Description|
|---|---|
|Stamina|The amount of times you can battle a mob|
|Strike|Power level of the player (will be explained in the tutorial)|
|Gear|Items you can equip > head, body, leggings, boots|
|Weapon|The weapon you are carrying|
|Traveling to| Traveling status|

Do n`start in a discord channel with the bot to begin


## Tutorial
You should be redirected here after using the n`tutorial command.

### Player commands
|Command|Description|
|---|---|
|`start`|Create an account|
|`map <locationn=current>`|Shows current location of player, type `<full>` to see the whole map
|`travel`|Set place that you want to go to|
|`move`| Travel 1 clik in the direction of the place you are traveling to|
|`stats`|Show player stats|

### Moving around
To travel the world of Neslogaia, you first need to set the directiuon of travel.

1. Use `map` to determine current location
2. Use `travel <place>` to set the place you are traveling to. `<place>` is the place you want to go to, the list of place you can go to is determined by your current location

Each place has a certain distance you need to move. This is determined by **cliks**.

3. Use `move` to move 1 clik in the direction of the place you are traveling. Note that you may encounter mobs while moving.

### Combat (Strike Zone)
When you encounter a mob, you will enter a battle wwith it. The combat system here is based on Strike Zone(tm), which is based on RNG. Here is how it works.

|Your Strike value|Mob's Strike value|
|---|---|
|10|5|

1. Both you and the mob's Strike value are combined top form the Strike Zone(tm), (10+5=15)
2. A random number from 1 to 15 will be generated

If the number falls between 1 to 10, you win. Else if the number falls between 11 to 15, you lose.

If you lose, your Stamina will be deducted by 1 and if it reaches 0, you will pass out and return the original place you were traveling from.

### Equipments
As you travel the world, mobs will have a higher Strike value. To increase your own Strike value, you need to equip better weapons and gears. They can be obtained from battling mobs and from shops.