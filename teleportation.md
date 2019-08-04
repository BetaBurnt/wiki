![ribbon](L-ribbon.png) 

# Basic Teleportation

To teleport to another player you must request it with the `/tpa [playername]` command to go to them, or `/tpahere [playername]` for them to come to you.
The player it is aimed at can then accept it with `/tpaccept` to allow the teleportation, deny it with `/tpdeny`, or simply ignore it!
>Please do not spam people with tp requests - if they have denied it or said no then this will be treated as harassment

## Locations

- `/survival`, `/surv` or `/spawn` will return you to the main spawn point in the Survival world.
- `/creative` will take you to the spawn point in the Creative world.
- `/resources` will take you to the spawn point of the current Resource world.
- `/pawnshop` will take you to the entrance of the servers admin/pawn shop.

## Homes
You can also set up to 3 homes for your own private teleportation spots!
- To set a home teleport use `/sethome [home name]`
- To go to one of your homes use `/home [home name]`
- And to delete one? `/delhome [home name]`

## The End and the Nether

To get to the Nether build a nether portal as normal.
To reach The End, find an end portal in the Resource World. The end is reset every 2 weeks.

## Player Warps

You can now set up to 10 player warps on your Creative plots to allow people to teleport over and view your builds at any time!
To do so stand where you want the teleport to be and do `/pwarp set <name>`, or `/pwarp remove <name>` to remove one you have already set!

You can list all player warps via `/pwarps` and either click the option on the list to go there, or do `/pwarp <teleport name>`!

## Player Shop Teleports

You can use various commands to allow others to teleport to your shop and to add your shop to a list of advertised shops.

Commands:
- Set your shop tp where you are with `/setshop`
- Go to your own shop with `/shop`
- Teleport to another players shop, if they have one, with `/shoptp <name>`
- Delete your shop teleport *and* advert with `/delshop`
- Lock/unlock your shop teleport with `/shoplock`

- List shops that have bought an advert in a menu, and click them to go to them, with `/shops`
- Set the message in your advert (colour codes allowed) with `/shopadvert <message>`
- Remove the message/lore entirely from your advert with `/clearshopadvert`
- Buy an advert in the /shops listing (which costs $5000) with `/buyadvert`

Shop adverts will last till the end of the month, regardless of when you buy it, as the adverts will wipe on the 1st of each month. If/when the plugin devs adds timed adverts their end I'll use that instead but for now it's an all or nothing advert wipe and I'd rather keep inactive shops out of the list.


The above commands are just masks that are a bit easier to remember/write - the normal commands are `/pshops <blah> <blah> <blah>`, and `/pshops help` will list all of the above.
