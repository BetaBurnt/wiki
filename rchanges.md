![ribbon](images/L-ribbon.png) 

# Changes We Make To Some Vanilla Mechanics

Not all Vanilla/singleplayer features are a good idea for multiplayer/server scenarios.
In fact - a **lot** of the stuff Mojang adds/changes is dumb as hell from a server perspective, because they don't really give a rats ass about servers (even less so about non-Realms servers... but that's a rant for another day).

As such we do make changes to a few Vanilla features - or "features" said very loosely, as a lot of the "features" we change are actually exploits, that people ytu to argue are "features". 
Any major ones that players are likely to notice/care about will be listed on this page.

> **Note that just because something is not listed on here does not mean we have not made changes to it, or a plugin isn't making changes to it (particularly if it's considered a bug/exploit - regardless of whether it's in Vanilla or not). This is just a lit of the main things.**

## Table of Contents
As a quick run down so you don't need to scroll down to find what you're looking for:
- [Anvil Repairing and Enchanting](#anvil-repairing-and-enchanting)
- [Aquiring Mending](#aquiring-mending)
- [Elytra Limits](#elytra-limits)
- [Hopper Limits](#hopper-limits)
- [ShulkerBox Recipe Tweak](#shulkerbox-recipe-tweak)
- [Nether Scaling](#nether-scaling)
- [Notable Explot Patches](#notable-exploit-patches)

## Anvil Repairing and Enchanting

Anvil repairing in Vanilla makes it a little too easy to avoid losing rarer equipment or enchants, and in some cases a little too easy to mix enchants from multiple items.
The "only X repairs per item" part of the mechanic doesn't really help limit it enough or give enough of a risk of loss - which is a major feature of Survival.

As such we do tweak how anvil repairing/enchanting works a little - for anyone that has played on a server with mcMMO, it works in a similar fashion to how their repair works (as this was added when we also had mcMMO prior to 1.16, when we switched to McRPG).
We do this in two ways:

**1**:
If both items are enchanted and combinable (and not an enchanted book) - so for example two diamond swords you want to merge the enchants on - it will mix the enchants as it normally would, however it will keep the durability level of the original item with the highest durability.

**2:**
If one item is enchanted and the other is not and they are combinable (and again, not an enchanted book) - so for example a damaged enchanted diamond sword and an unenchanted diamond sword, intention being to repair the enchanted sword - then there is a risk of losing or downgrading your enchantments in the repair process.

When you attempt this you will be given a warning about this, and the repair will be cancelled (this warning triggers the first time, and every 10th repair after as a reminder) - if you run it again the repair will go through.<br>
When the repair goes through there is a 20% chance of losing the enchantments entirely - if that doesn't happen, there is a 40% chance that just one enchantment will be removed (but it's not guaranteed that one will, there's a luck roll donw on each enchant and if any fail they're removed - once one is removed the rest are not rolled for). <br>
If neither triggers you will keep the enchantments as they are.

The only guarantee to repair an item in full and keep it's enchantments is to use the repair sign at the server spawn.

**Note:**
Anvils will work normally when both items are unenchanted, only one item is present (ie renaming an item) or if one of the items is an enchanted book.


## Aquiring Mending

Mending - to put it bluntly - is one of the **dumbest** things to ever be added to Minecraft when it comes to multiplayer/server situations. 
It may be extremely useful as a player, and almost necessary on singleplayer - but it is **far** too easy to get, particularly when abusing certain exploits, and makes the risk of losing equipment considerably lower to the point of it basically not being Survival any more. 

From a server/multiplayer perspective this causes **many** issues longterm - As such we're limiting the ways you can get it to make it considerably less farmable.

You will still be able to find Mending books in dungeon/treasure chests around the world as you normally would in Vanilla - however, you will not be able to trade for them with Villagers.

Instead, as an extra few ways they can be gained, you have a chance to gain Mending books on days 14 and 28 of your DailyBonus rewards through Bonus Bill and they will be given out as Top Voter and Build Competition rewards as well.


## Elytra Limits

Elytras... another extremely dumb thing Mojang have added. Not for what it allows you to do, but for the fact it is not limited in almost any way - to the point they made the item unbreakable, which is **beyond** dumb in a server scenario where they almost never end up staying rare for long - and that it is **SO** easy to kill a server with them, when you add the **MANY** serverside performance issues Mojang has now ignored for years (such as the major issues chunk loading/generation causes... you know - that you load a BUTTLOAD of in when flying around with an Elytra and rockets...?).

To try and limit this somewhat a few things have been changed with how Elytras work.
**1** - They **are** breakable. We reset our End once a month, and you can get Elytras through the Token Shop - they aren't extremely rare, and in a Survival game everything should have some amount of risk of being broken/lost.
**2** - Using rockets to boost your flight will damage your Elytra. It's only a small amount of damage per rocket use, but if you use a lot - it will quickly deplete your Elytras durability (and if it hits 0 it **will** break, so keep an eye on it).
**3** - You cannot eat or drink potions etc... while gliding with your Elytra. To fill your hunger/heal up you will need to land.
**4** - Riptide use will interrupt your gliding, so you cannot endlessly fly about in the rain.


## Hopper Limits

By this point it should be fairly common knowledge that one of the many things that are poorly optimised and highly prone to cause server TPS drops and majpr lag issues.... are Hoppers.

In general - if you don't **need** to place many hoppers, then don't. For example: You don't need to make an item sorter for every item in the game - that many hoppers **will** cause server issues, and it doesn't take you **that** much longer to sort your chests yourself.
However - to keep potential problems from overuse of hoppers down there are two things we have done:

**1**: - Added Upgradeable Hoppers. You can read up on them [HERE](hopper.md).
**2**: - Limited how many hoppers you can have in one chunk to 50. You physically won't be able to place any more once a 50th has been placed in the same chunk (this applies to Upgradeable Hoppers too, but as they work completely differently you would never need 50 of them in one chunk).


## ShulkerBox Recipe Tweak

ShulkerBoxes are too easy to craft - it is very very easy to get shulker shells on multiplayer servers (as it only takes one person to go farm shulkers in the End and then sell them to allow **everybody** to have all the shells they'll ever need) and only requiring 2 for a box is ridiculous.

As such we have tweaked it to require 8 shells per shulker box, as it is still easy enough to get that many and it helps limit how many shulkerboxes are floating around.

![shulkerbox](images/shulkerboxes.png)
(Will add image another time)


## Nether Scaling

The scaling between the Overworld and Nether has been abusable for as long as the Nether has existed. 
If you don't know what I mean by this I mean the fact that every 1 chunk in the Nether is 8 chunks in the Overworld - allowing for the use of fast travelling around the Overworld without anybody knowing, by going into the Nether, walking 1/8th of the distance you want to go and building a portal to the Overworld.

It also makes it annoying as hell to set world borders correctly without any risk of bugging when people go between these worlds and accidentally dropping them outside of a world border.
As such we have changed the scaling for our Nether worlds.

The default scaling is 1:8 (Nether:Overworld) - in our Survival Nether world it has been reduced to 1:2 and in our Resource Nether world it has been reduced to 1:4.


## Notable Exploit Patches

### Villager Trade Cheesing
Removing Mending from Villager trades is not the only thing we have changed with Villager trades.
The feature added where if you cure a Zombie Villager they give you a discount? That's the feature. Where you re0=-infect and cure and repeat to get 1 emerald trades for rarer shit (like enchant books)? **That's an exploit**.

As such a Villager cannot be turned back into a Zombie Villager once cured. The initial discount they give you is all they will give.

Other than these two things, Villager trading works as normal.

### Zero Tick Farms
Not a feature - never has been, never will be. It has been an exploit from the second it became doable. These are disabled.

### Various Duplication Glitches
A prime example being the mob chest duplication glitch. This is patched and will not work.

### Nether Roof Access
It is not supposed to be accessible, never has been - that is the point of there being a flat layer of bedrock there, you can't get through it by normal Survival means only by abusing glitches/bugs.

### Offhand Tool Looting Exploit
The exploit - having a tool in your offhand such as a bow that does not have looting, and a sword in your main hand that has looting. You use the bow - it applies the looting from your sword to it even though the bow does not have looting itself.

This is patched - **however** it should be noted that currently the way it gets patched is just to disable looting from working when you have tools in both hands, so to use looting, don't dual-weild. If a better patch comes up I'll swap it to that.

**There are other bugs/glitches/exploits patched but these are the main, notable ones**.
