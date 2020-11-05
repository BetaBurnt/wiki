![ribbon](images/L-ribbon.png) 

# Towny

LegionCraft employs the use of the Towny plugin - this allows you to band together with your friends, build an area to live in together and then claim the area for yourselves using ingame money (which you can earn through jobs and via shops)!

**--But why should I make or join a Town?**
Do you like leaving your builds at the risk of a random player coming along and breaking it, stealing stuff, killing your animals etc...? If not - join/make a Town!
Living on town land makes it so that only other residents of your town can build or destroy your stuff unless you specifically give them permission to do so!
Towns also allow you to toggle certain things in the claimed area such as mob spawning or PvP, give you an extra teleport to your stuff with `/t spawn`, access to private chat channels for just the residents of your town or members of your nation/allied nations among a few other things!

>When choosing somewhere to set up your town please remember to travel away from the spawn area and other towns - the closer to spawn or commonly accessed areas you are, the more likely that players will find your stuff and grief your builds until they are claimed and protected.


## Creating your Town

To create your town you must first find somewhere to build - as when you create the town the area you are stood in will be claimed as your towns home/first chunk of land!
When you know where you wish to build, use the `/t new [town name]` command to create your town!

**Note:**
Starting a Town will cost $2500 from your player balance - though in general make sure you have plenty extra to cover ongoing costs, land claiming costs etc... (the various costs can be found below).
Until you have the money to start and set up your town you can simply `/sethome` at your build area to get back, just remember that until it is claimed it is griefable by all!


## Expanding your land

You can then expand land with the `/t claim` command when stood in a chunk of land adjacent to land you already own. 
The amount of chunks you can claim are dependant on how many players have joined your town - when it is only yourself in the town you will be able to claim up to 20 chunks of land, which will increase as you add more residents or if you join a Nation (see table further down the page)!

You can also claim an outpost, meaning a chunk of land that is not connected to the rest of your town (for example if you wish to claim land for a new resident that already built elsewhere) by using the `/t claim oupost` command. You can use the normal `/t claim` command to claim land adjacent to an outpost as well as your main Town area!

To remove your claim on a chunk of a land do `/t unclaim` whilst stood in the chunk you wish to unclaim.

### Warning Regarding Claiming Land

You **are not allowed** to create a town, claim land or claim an outpost where another player lives/has built without their express permission! 
Anybody found to have done this will have the land unclaimed (no refund on the claim costs) and will either be warned or tempbanned as a result, depending on the circumstances.

## Inviting Players To Your Town or Joining A Town

To invite someone to join your town use the `/t add [name]` command.

If you wish to kick a player for any reason use `/t kick [name]`

If you do not wish to create your own town, and would rather join one that is already active, you can list the available towns with `/t list`, and view information such as who the mayor is with `/t [town name]`. Make sure to ask the relevant players if you can join their town!

To leave a town at any time use `/t leave` - Please make sure to remove anything of yours from the town first as the town Mayor is not obligated to give you those items back! 

### Resident Locks in Town Land
Just a quick note before continuing with the main Towny information - If your town goes under because it cannot cover the daily upkeep any locks on chests/doors/gates etc... in that land will be unlcoked at the same time and become fair game to raiders. The same applies to locks on a chunk that you unclaim yourself.

Note that kicking a player from your town does not lift any locks they've made on your town land. You can have staff remove those locks if you open a ticket by them.


## Town/Nation Teleportation

You can teleport to the spawn point of your own town at any time for free using `/t spawn`!
The spawn can only be in the home block of your town:

- To change the towns home block to another claimed chunk stand in the new chunk and use `/t set homeblock`
- To move the towns `/t spawn` stand where you want it to be in the home block and use `/t set spawn`

You can teleport to another towns spawn using the `/t spawn [town name]` command, but only if the town Mayor has enabled this (it is disabled by default)!

To enable/disable your town spawn from being used use the command `/t toggle public`.


## Town Costs

Remember that towns, the lands you claim for them, and nations are not free! 

Always make sure to have enough money in the town bank to cover expansions/claims and the daily upkeep - to deposit money in the town or nation bank use the `/t deposit [amount]` and `/n deposit [amount]` commands!
Only a town/nation owner can withdraw from the bank with `/t withdraw [amount]` and `/n withdraw [amount]`! If you are not the owner please be sure that you wish to donate your money to the bank before depositing it!

The costs of setting up and running your town/nation are as follows:

- To create the town itself it will cost you $2500 from your own balance - so please make sure that you are sure of where you wish to build, and have the funds, before setting it up as this will not be refunded if you change your mind!
- To create a nation it will cost you $50000 from your own balance.
- To claim extra chunks it will withdraw $350 from your town bank for each chunk you claim.
- To claim an outpost (a chunk of land not connected to the rest of your town) it will withdraw $1500 from your town bank for each outpost claimed.

**Note**:
Your Town Bank can only hold up to $10,000,000 at a time.

## Town Level Information

As more players join your Town it will grow in size, go up between the Town levels, and will become more expensive to keep running.

This table will show you when the Town will change levels (based on the number of residents in the Town) and when it does how the daily upkeep and number of claims changes.
Your Town bank must **always** have enough to cover the daily upkeep - these are taken once every 24 hours realtime and if a Town does not have enough money to cover the upkeep (and does not have taxes set up to take money from residents to cover the upkeep) then it will be disbanded.

|Town Level|Number of Residents|Daily Upkeep|Max Number of Outposts|Max Number of Chunk Claims|
|---|---|---|---|---|
|Settlement|1 Player|$3,500|0|20|
|Hamlet|2-4 Players|$3,500 per Resident|1|40|
|Village|5-9 Players|$7,000 per Resident|1|60|
|Town|10-14 Players|$10,500 per Resident|2|85|
|Large Town|15-19 Players|$14,000 per Resident|3|100|
|City|20-24 Players|$17,500 per Resident|3|120|
|Large City|25-29 Players|$21,000 per Resident|4|140|
|Metropolis|30-34 Players|$24,500 per Resident|5|160|
||35-39 Players|$28,000 per Resident|||
|Megalopolis|40-44 Players|$31,500 per Resident|6|180|
||44-49 Players|$35,000 per Resident|||
|Utopia|50+ Players|$1,750,000 (At 50 residents this is $35,000 per resident - less if you have more residents).|6|200|

**Note:** While the upkeep costs may look daunting as they go up, remember that as they go up there is also more residents to split it between (so more people to contribute to the upkeep where others can't). As your jobs go up it will also be **very** easy to manage this.

## Nations

Nations are a group of towns that are essentially allied to each other. 
This allows you to use their town spawn even if it's disabled publically, it will increase how many chunks you can claim for your town and will also allow you to talk to players in your nation without talking to those not in your nation with the nation chat channel! (see below).

To create a nation use the command `/n new [nation name]`. 
This can be done anywhere, as it does not claim land - your own town will automatically be the capital of the nation, with you as the King!

## Nation Level Information

As with Towns, as more Towns join your Nation (and as such more residents become part of your Nation) it will grow in size, go up between the Nation levels, and will become more expensive to keep running.

This table will show you when the Nation will change levels (based on the number of residents in the Nation, not the number of Towns themselves) and when it does how the daily upkeep and number of bonus claims changes.
Your Nation bank must **always** have enough to cover the daily upkeep - these are taken once every 24 hours realtime and if a Nation does not have enough money to cover the upkeep (and does not have taxes set up to take money from residents to cover the upkeep) then it will be disbanded.

|Nation Level|Number of Residents|Daily Upkeep|Max Number of Bonus Claims Towns In The Nation Receive|
|---|---|---|---|
|Nation|1-14 Residents|$50,000|10|
|Nation|15-29 Residents|$200,000|50|
|Nation|30-49 Residents|$400,000|100|
|Nation|50-69 Residents|$750,000|150|
|Empire|70-99 Residents|$1,200,000|200|
|Realm|100+ Residents|$1,750,000|250|

**Note:** As with Towns, while the upkeep costs may look daunting as they go up, remember that as they go up there is also more residents to split it between. As your jobs go up it will also be **very** easy to manage this.

**Note 2**:
As with the Town Bank your Nation Bank has a cap on how much it can hold at a time - which is up to $25,000,000.

## Chat Channels

Towny allows the use of multiple chat channels to allow you to speak to specific players in private!

These channels are:

- `/g`, `/general` or `/global` - The Global channel which you are in by default and allows all players on the server to see what you are saying.
- `/tc` or `/tchat` - The Town channel which allows only residents of your own town to see what you are saying.
- `/nc` or `/nchat` - The Nation channel which allows residents of all towns in your nation to see what you are saying.
- `/ac` or `/achat` - The Ally channel which allows residents of all towns in your nation and residents in any allied nation to see what you are saying.


## Notes

For anything not covered in this post please refer to the [official command list for Towny](https://github.com/TownyAdvanced/Towny/wiki/Towny-Commands). 
Note that you will obviously not have access to any admin commands, and you will only be able to use commands that you are a relevant rank in the town to use (eg: only the Mayor can change the name of the town or withdraw from the bank etc...).
The sections relevant to you are the `/towny`, `/plot`, `/resident`, `/town` and `/nation` sections. 
