# CyberTweaks
Tweaks Minecraft to have better crafting, and an optional periodic global item despawn!

# Crafting

Adds 2x2 crafting for paper, bread, and other items

Will eventually support custom crafting

# Other things

Will add support for plugins to the datapack in the 'cybertweaks/data/plugins' folder

You will need to list the load function in the 'cybertweaks/data/main/functions/load.mcfunction' file

If the plugin adds any items, you will need to register them in the 'cybertweaks/data/custom/items/functions/citems.mcfunction'

EXAMPLE: (Replace "'" with "#")

'{itemname}

function plugins:{itemname}

function plugins:{itemmeta} (IF NEEDED)

function plugins:{itemdroprecipe} (IF NEEDED)

If the plugin adds any custom recipes (When implemented), you will need to register them in the 'cybertweaks/data/custom/recipes/functions/crecipes.mcfunction'

EXAMPLE: (Replace "'" with "#")

'{itemname}

function plugins:{itemrecipe}
