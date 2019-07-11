# Towny

![towny](http://image.prntscr.com/image/261556e23e144a3ead07d5023075452e.png)

LegionCraft employs the use of the Towny plugin - this allows you to band together with your friends, build an area to live in together and then claim the area for yourselves using ingame money (which you can earn through jobs and via shops)!
Claiming your area allows you to toggle certain things in that area (such as mob spawning or PvP), protect against grief/control who can build in the claimed land and set a town spawn so you don't need to use one of your homes to get home!

>When choosing somewhere to set up your town please make sure to travel away from the spawn area - the closer to spawn you are, the more likely that new players who have not read the rules (or ignored them) will grief your builds until they are claimed and protected. While we can roll the damage back, it is an inconvenience that is easily avoided!


## Creating your Town

To create your town you must first find somewhere to build - as when you create the town the area you are stood in will be claimed as your towns home/first chunk of land!
When you know where you wish to build, use the `/t new [town name]` command to create your town!


## Expanding your land

You can then expand land with the `/t claim` command when stood in a chunk of land adjacent to land you already own. The amount of chunks you can claim are dependant on how many players have joined your town - when it is only yourself in the town you will be able to claim up to 16 chunks of land, which will increase as you add more residents or if you join a Nation!

You can also claim an outpost, meaning a chunk of land that is not connected to the rest of your town (for example if you wish to claim land for a new resident that already built elsewhere) by using the `/t claim oupost` command. You can use the normal `/t claim` command to claim land adjacent to an outpost as well as your main Town area!

To remove your claim on a chunk of a land do `/t unclaim` whilst stood in the chunk you wish to unclaim.


Inviting players to your town, or joining a town that has already been made:

To invite someone to join your town use the `/t add [name]` command.

If you wish to kick a player for any reason use `/t kick [name]`

>Note that doing this does not give you the rights to their building/items etc... If you want their stuff removed from the town please contact a Mod+ or higher, or submit a `/report` next to their building requesting it.

If you do not wish to create your own town, and would rather join one that is already active, you can list the available towns with `/t list`, and view information such as who the mayor is with `/t [town name]`. Make sure to ask the relevant players if you can join their town!

To leave a town at any time use `/t leave` - Please make sure to remove anything of yours from the town first! You will not be able to build etc... on their land once you leave!


## Town/Nation Teleportation

You can teleport to the spawn point of your own town at any time for free using `/t spawn`!
The spawn can only be in the home block of your town:

- To change the towns home block to another claimed chunk stand in the new chunk and use `/t set homeblock`
- To move the towns `/t spawn` stand where you want it to be in the home block and use `/t set spawn`

You can teleport to another towns spawn using the `/t spawn [town name]` command, but this may be disabled and may cost a small amount of money!

To disable your town spawn from being used use the command `/t toggle public`.

To use the spawn of another town that is not part of the same nation as you (if you are in one) it will cost you $100 per spawn, and if you are in the same nation it will cost $50!


## Prices

Remember that towns, and the lands you claim for it, and nations are not free! Always make sure to have enough money in the town bank to cover expansions/claims and the daily upkeep - to deposit money in the town or nation bank use the `/t deposit [amount]` and `/n deposit [amount]` commands!

The costs of setting up and running your town/nation are as follows:

- To create the town itself it will cost you $5000 from your own balance - so please make sure that you are sure of where you wish to build, and have the funds, before setting it up as this will not be refunded if you change your mind!
- To create a nation it will cost you $50000 from your own balance.
- To claim extra chunks it will withdraw $150 from your town bank for each chunk you claim.
- To claim an outpost (a chunk of land not connected to the rest of your town) it will withdraw $500 from your town bank for each outpost claimed.
- The daily tax/upkeep to keep the town is $5000 per day for your town, and $50000 each day for a nation, which is taken from the town/nation bank balance. This will increase the more residents there are in your town, and the more towns there are in your nation - Make sure to keep an eye on the costs and your town/nation bank balance at all times!

Only a town/nation owner can withdraw from the bank with `/t withdraw [amount]` and `/n withdraw [amount]`! If you are not the owner please be sure that you wish to donate your money to the bank before depositing it!

## Nations

Nations are a group of towns that are essentially allied to each other. This allows you to use their town spawn for half the price, it will increase how many chunks you can claim for your town, and will also allow you to talk to players in your nation without talking to those not in your nation with the nation chat channel! (see below).

To create a nation use the command `/n new [nation name]`. This can be done anywhere, as it does not claim land - your own town will automatically be the capital of the nation!

## Chat Channels

Towny allows the use of multiple chat channels to allow you to speak to specific players in private!

These channels are:

- `/g` - The Global channel which you are in by default and allows all players on the server to see what you are saying.
- `/tc` - The Town channel which allows only residents of your own town to see what you are saying.
- `/nc` - The Nation channel which allows residents of all towns in your nation to see what you are saying.


## Notes

For anything not covered in this post please refer to the [official command list for Towny](http://towny.palmergames.com/towny/towny-commands/). Note that you will not have access to any admin commands, and you will only be able to use commands that you are a relevant rank in the town to use (eg: only the owner can change the name of the town or withdraw from the bank etc...).
The sections relevant to you are the `/towny`, `/plot`, `/resident`, `/town` and `/nation` sections. 
