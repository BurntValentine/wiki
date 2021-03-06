![ribbon](images/L-ribbon.png) 


# MicroChests

![mchests](images/mchest.png)

You can also create MicroChests! These will allow for up to 6 rows (54 slots) of storage in one space! To start you will need to craft a Wooden MicroChest (oak planks only):

![wchest](images/microchest.png)

When placed and right clicked (when not sneaking) this will grant you a 9 slot/1 row chest that only you and staff will have access to - you can also give/remove access to any chests you own via:
- `/mchest grant <player>`
- `/mchest revoke <player>`

Players with access cannot break your microchest - they can only add items to and remove items from the storage!

While you have a microchest placed you can also upgrade it to increase its space! The order of upgrades goes Wood > Iron > Gold > Obsidian > Emerald > Diamond - each upgrade adds a row/9 slots of extra storage, with Diamond allowing for the same storage a double chest would grant, but in one space!
To upgrade the microchest you will need to craft an upgrade paper! To do so follow this format with the bottom 3 items being the chests current material and the 5 items around the outside being the new material:

![w2i](images/w2i.png)

To go from Obsidian > Emerald or from Emerald > Diamond, replace the chest in the recipe for an EnderChest as well - for example:

![o2e](images/o2e.png)

When you have your upgrade papers, hold it and sneak right click on the microchest to upgrade it!
Please note that when you upgrade the microchest it will automatically have increased storage (any items it had will still be there), but it will not look any different (due to Skript limitations). When you break the microchest however it will return the upgraded item to you (ie if you place a wood microchest and upgrade it all the way to diamond, and then break it - you'll be given a diamond microchest not a wood microchest).

If you need to for any reason you can see who owns a microchest with:
- `/mchest check`

When you break a microchest it will add the chest item and any items that were stored in it into your inventory directly - if you do not have enough space in your inventory any excess will drop where you are standing (not where the chest is, just in case).
