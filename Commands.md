# AsilosX Documents

## About Asillage
Asillage is the where player enters the game and the place that everythings starts. Asillage is the hearth of this game.
Asillage has a buildings that you can go with commands. If you go to somewhere, you can do something in there. Example, if you go shop you can buy something or sell something, but you can't perform that action from another location.
##### x!asillage
You go to main square of Asillage. Sometimes, you will be notified by a message and It will tell you, you saw something and you can interact with them.
And also, this command will list you random 10 player who is in here too from your guild.

Location Name: `asillage` 

You can perform these commands in this location:
- **x!villager <name>**
Talks with name specified villager. They may give you quests or make jokes.

- **x!getclose <thing>**
You get closer to that thing. That thing may be `villager, item, pet`. When you get close that thing, you may get hurt, get quests or find somethings. Your chance is based on your `LUCK` perk.

##### x!asilshop
You go to shop of Asillage. You can buy or sell somethings in here. If you have higher `INTELLIGENCE` and `CHARISMA` you may buy something under-value or sell something higher-value. 

Location Name: `asilshop` 

- **x!goodies**
Lists shop items. It may be weapon, pet, armor, resources or misc. items. The shop will get freshed based on your `STRENGHT`, `CHARISMA` or `LEVEL`   

- **x!buy <ammount> <thing>**
Buys that thing.

- **x!sell <ammount> <thing>**
Sells that thing.

- **x!info <thing>**
Shows info about that thing.

##### x!asilsmith
You go to ironsmith of Asillage. You can craft sword or armor here or upgrade your sword, armor. When you upgrade your item, you will need resources and it may be unsuccessful then you will lose your resources. You need `LUCK` to prevent this.

Location Name: `asilsmith` 

- **x!informations**
It shows which item you can forge.

- **x!forge <item>**
You craft that item.

- **x!info <item>**
You get info about that item.

- **x!upgrade <item>**
You upgrade that item.

##### x!asilhall
You go to hall of Asillage. You can pay your taxes here and see wanted list.

Location Name: `asilhall` 

- **x!tax**
  - **x!tax pay <amount>**
It pays amount of your taxes.

  - **x!tax info**
It shows you how much you have to pay to government.

- **x!wanted**
Lists 3 people who is wanted.


## About Economy
There is a Economy in Asillage. You can buy things and sell things of course. But also, you can give part of your coins to poor people, or you can toss a coin to your witcher.
- **x!coins**
Shows your coins. (You can not look at another else's coins)
- **x!pay <ammount> @user**
You give specified coins to menitoned user.
- **x!onlineshop (DONATORS ONLY)**
You can buy anything from anywhere.
  - **x!goodies**
Lists shop items. It may be weapon, pet, armor, resources or misc. items. The shop will get freshed based on your `STRENGHT`, `CHARISMA` or `LEVEL`   
  - **x!buy <ammount> <thing>**
Buys that thing.

  - **x!sell <ammount> <thing>**
Sells that thing.
  - **x!info <thing>  **
Shows info about that thing.

- **x!tosscoin <ammount>**
You toss specified ammount of coins to road. You may gain `PERCEPTION` or `CHARISMA`

-** x!steal**
You try to steal something from someone. It asks 3 options. The options will be labeled as "A", "B" or "C" in background.
  - *If player choose A*
    - %30 chance to find 100-200 credits and %10 chance to loose 1 `CHARISMA`
    - %30 chance to find 201-500 credits and %15 chance to loose 1 `CHARISMA`
    - %30 chance to find 501-1500 credits and %20 chance to loose 1 `CHARISMA` or %25 chance to loose 1 `LUCK`
    - %10 chance to find nothing
  - *If player choose B*
    - %50 chance to full HP and %30 chance to loose 1 `LUCK`
    - %20 chance to full SP and %60 chance to loose 1 `LUCK`
    - %30 chance to find nothing
  - *If player choose C*
    - You couldn't steal anything...


## About Inventory
Every player have an Inventory that keeps everything that they found. There are 4 item categories, `Weapons, Armors, Resources, Miscellaneous`
- **x!inventory**
Shows every item you have.
  - **x!inventory <weapons|armors|resources|misc> <page>**
  Shows only items in selected category. Also you can switch pages.

- **x!use <item> <ammount>**
Uses that item with specified ammount.

- **x!drop <item> <ammount>**
Drops that item with specified ammount.

- **x!gift @etiket <item> <ammount>**
Gifts that item with specified ammount to mentioned user.

- **x!combine <item1> <item2>**
Combines 2 item to make resources. `item1` and `item2` must be in same category.

- **x!equip <equipment>**
If you have enougth stats to eqip that item you equip that item.

- **x!iteminfo <item>**
Gives info about that item.

## About Pet System
- **x!pets <page>**
Lists every pet you have.
- **x!pet**
  - **x!pet <pet name>** or **x!pet info <pet name>**
  Shows your pet.
  - **x!pet <info> <pet name>**
  Shows info about your pet.
- **x!train**
  - **x!train <pet name>**
  Trains your pet.
  - **x!trains <pet name> <item name>**
  Trains your pet with special item. You may get higher train rates with this.
  
- **x!setclass <pet name> <warrior, banker, clown>**
Changes pet's class

- **x!setfriend <pet name>**
Sets default pet that will be used in fights.

- **x!cagetrain <pet1 name> <pet2 name>**
Trains in a cage your pets. Your pets will lose HP in this but you may get higher train rates with this.

- **x!eject <pet name>**
You part ways with that pet...


## About Stats
What makes you is your stats. They are very important to win a fight. In fights, you will be matched in an equivalent traits to the pet's traits.

S : strength
P : perception
E : education
C : charisma
I : intelligence
A : agility
L : luck

HP : Health Point
SP : Stealth Point

M.HP : Max Health Point
M.SP : Max Stealth Point

## About Classes
Every pet have a class. It can be changed later but your traits will be resetted to default. The classes are in down below.
#### CLASS 1: Warrior
S: 5
P: 1
E: 1
C: 2
I: 3
A: 4
L: 2

M.HP: 150
M.SP: 50

#### CLASS 2: Banker
S: 1
P: 1
E: 4
C: 3
I: 3
A: 2
L: 4

M.HP: 100
M.SP: 100

#### CLAS 3: Clown
S: 2
P: 1
E: 1
C: 5
I: 1
A: 6
L: 2

M.HP: 80
M.SP: 120


## ABOUT PVP SYSTEM (Pet vs Pet)
There is a PVP system that you can fight with your pets only. Fighting will gain you `LEVEL` and `STRENGHT` to you and your pet.
If you made opponent's HP to 1 you may show mercy to it or kill it. It is your decision. Also, if you are not winning the fight, you can try to escape. The default chance is 20% but if you have higher `AGILITY` your chance will be increased.
- **x!fight**
You fight with selected pet to random pet or to specified player's pet.
  - **x!fight <pet> @player**
  Your pet fights with mentioned player's default pet.
  
  - **x!finishhim**
  Kills the opponent.
  - **x!mercy**
  Forgives the opponent.
  - **x!escape**
  Tries to escape.
