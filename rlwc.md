![ribbon](images/L-ribbon.png) 

# Locking your valuables

On LegionCraft we use LWC for block protection.

**Nothing will lock automatically** - this is a grief-and-raiding-allowed server, so if you want to protect some valuables you need to make sure you lock them!
Anything locked will be unbreakable/lootable to anybody but the player that locked them (they can be raided by people you give access to specifically) - **however** locks are not permanent. 
If you are not online for more than 28 days all of your locks will lift and your stuff becomes fair game for greifers/looters again - The only way to guarantee protection for things long term is to have a town with adequate funds to keep it alive!

The following can be locked:
- Chests (Single, Double, Trapped)
- Droppers
- Furnaces
- Blast Furnaces
- Smokers
- Barrels (MC barrels, not Brewery barrels)
- Dispensers
- Signs
- Doors
- Gates
- Trapdoors
- Chest/Furnace Minecarts
- Item Frames
- Armor Stands
- Shulker Boxes
- Dragon Eggs

To lock any of the above simply do `/lock` and punch the block.
Some useful commands for locks:
- `/cmodify [player]` - Give access to one of your locked doors/chests etc... to the named player. To remove access run the command again but put a - infront of the player name (eg `/cmodify -burntvalentine).
- `/unlock` - Self explanatory.
- `/cpassword [password]` - Do this on an **unlocked** block to lock it with a password so only those with the password can access it.
- `/lwc flag autoclose` - Will set the door/trapdoor/gate you punch after to close a few seconds after it is opened automatically, without the need for a pressure plate.
- `/cpersist` - Run this and then the command you wish to persist to keep doing it. For example do `/cpersist` and then `/lock` to be able to walk around a room of chests and punch each one to lock them without needing to run the command many times. Do `/cpersist` again to stop it.
- `/cpublic` - Do this on an **unlocked** block to allow anybody to access it but not break it.
- `/cdonate` - Do this on an **unlocked** chest to allow people to put items INTO the chest but not take them OUT of the chest.

You can also give/remove access to **everything** you have locked via:
- `/trust add [player]` - Give access to all of your locks.
- `/trust remove [player]` - Remove full access.
- `/trust list` - List who you have given full access to.
Note that this does not change normal permissions set with `/cmodify` etc.. (ie if you give someone access to one chest, then give them full access via `/trust add` and later on do `/trust remove` they will still have access to that specific chest you `/cmodify`'d for them).
