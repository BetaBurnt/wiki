![ribbon](images/L-ribbon.png) 

# Jump Pads

These are pressure plates that when set up will launch people who walk onto them, at varied powers/angles/directions depending on how you set them up!

These will unlock for you to be able to create at level 24!

Commands:
- `/jp create` - This will create a jump pad on the pressure plate you're looking at, and will give it the power you enter (up to 50) and the launch angle you set.
When a player walks onto the pad it will launch them in the rough direction they were looking with the power you entered and the angle it is set to.
- `/jp set` - This will allow you to change the power, direction (by default it's dependant on what direction you walk onto it), angle and particle that is on the jump pad. 

All particles will be listed when you do `/jp set particle` but not all work that well so::
- Particles that work correctly:
BARRIER, BUBBLE_COLUMN_UP, COMPOSTER, CURRENT_DOWN, DOLPHIN, DRIP_LAVA, DRIP_WATER, DRIPPING_HONEY, EXPLOSION_LARGE, FALLING_HONEY, FALLING_LAVA, FALLING_WATER, FALLING_NECTAR, HEART, LANDING_HONEY, LANDING_LAVA, LAVA, NOTE, REDSTONE, SLIME, SNOW_SHOVEL, SNOWBALL, SPELL, SPELL_INSTANT, SPELL_MOB, SPELL_MOB_AMBIENT, SPELL_WITCH, SWEEP_ATTACK, TOWN_AURA, VILLAGER_ANGRY, VILLAGER_HAPPY, WATER_BUBBLE, WATER_DROP,
SUSPENDED and SUSPENDED_DEPTH also "work" but they're barely visible so not worth it.

Other particles have issues with staying on the actual pad, and either fly off for a long distance or are extremely annoying - you can use other options if you wish but be sensible. Particles that fly off for a very long distance should be avoided.

- You can also change the colour of some of the particles with `/jp set color` (the tablist will list all available colours).
Particles that you can change the colour of:
REDSTONE, SPELL_MOB and SPELL_MOB_AMBIENT

To remove it simply break the pressure plate, or look at it and do `/jp delete`.


The only options that we will explicitly state are __**NOT**__ permitted to be used, and reports of them being used and left on to annoy people will receive warnings for, are:
- MOB_APPEARANCE
- EXPLOSION_LARGE
- FLASH




# Gravity Tubes

These are pillars of particles that provide a gravity-free lift for players that walk into them - To drop when you're in a tube just crouch!

These will also unlock for you to create at level 24, however - these unlock in stages when it comes to how high you can set them to go!
 Level 24 - Up to 10 blocks
 Level 34 - Up to 20 blocks
 Level 44 - Up to 30 blocks
 Level 54 - Up to 40 blocks
 Level 64+ - Up to 50 blocks
 
 Commands:
 - `/gt create [height] [speed]` - This will create a gravity tube at the block you are looking at that will go up as far as the height you entered, and lift players in the tube at the speed you set (1-10). The tube will also have swirling particle effects to make it visible.
 - `/gt set [setting] [value]` -  You can use this command to change the height and speed of the tube you're looking at the base block of, or to change the colour of the swirls (the tablist for `/gt set color` will list all available colours).
 
 To remove it simply break the block, or look at the block it's set to and do `/gt delete`.
