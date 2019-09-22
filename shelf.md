![ribbon](L-ribbon.png) 

# Bookshelf Storage

![shelf](https://i.gyazo.com/cce22cbe021e395ef177ec81651678e4.png) 

You can create a 9 slot storage in any bookshelf you have placed, lock/unlock it and give access to other players when it's locked!

The commands for this feature are (all require looking at the bookshelf it's for):
- `/bshelf set` to create a 9 slot storage in the target bookshelf.
- `/bshelf lock` to lock the target bookshelf so that only you (and staff) have access to it, along with those you grant access to.
- `/bshelf grant <player>` to give the named player access to the locked bookshelf you are looking at.
- `/bshelf revoke <player>` to remove the named players access from your locked bookshelf.
- `/bshelf check` to check who you have given access to (only works on a locked shelf you own).
- `/bshelf remove` to remove the bookshelf (the storage, not the block). Stored items in the shelf will be put straight into your inventory, or dropped where you are if you don't have space. Alternatively - break the bookshelf.


# MicroChests

![mchests](https://i.gyazo.com/d95d7999614991eb80710e237fcaecc7.png)

You can also create MicroChests! These will allow for up to 6 rows (54 slots) of storage in one space! To start you will need to craft a Wooden MicroChest (oak planks only):

![wchest](http://minecraftrecipedesigner.com/creations/235943.png)

When placed and right clicked (when not sneaking) this will grant you a 9 slot/1 row chest that only you and staff will have access to - you can also give/remove access to any chests you own via:
- `/mchest grant <player>`
- `/mchest revoke <player>`
Players with access cannot break your microchest - they can only add items to and remove items from the storage!

While you have chest placed you can also upgrade it to increase it's space! The order of upgrades goes Wood > Iron > Gold > Obsidian > Emerald > Diamond - each upgrade adds a row/9 slots of extra storage, with Diamond allowing for the same storage a double chest would grant, but in one space!
To upgrade the chest you will need to craft an upgrade paper! To do so follow this format, with the bottom 3 items being the chests current material and the 5 items around the outside being the new material:

![w2i](http://minecraftrecipedesigner.com/creations/235942.png)

To go from Obsidian > Emerald or from Emerald > Diamond, replace the chest in the recipe for an EnderChest as well - for example:

![o2e](http://minecraftrecipedesigner.com/creations/235940.png)

When you have your upgrade papers, hold it and sneak right click on the chest to upgrade it!
Please note that when you upgrade the chest it will automatically have increased storage (any items it had will still be there), but it will not look any different (due to Skript limitations). When you break the chest however it will return the upgraded item to you (ie if you place a wood chest and upgrade it all the way to diamond, and then break it - you'll be given a diamond chest not a wood chest).

When you break a microchest it will add the chest item and any items that were stored in it into your inventory directly - if you do not have enough space in your inventory any excess will drop where you are standing (not where the chest is, just in case).
