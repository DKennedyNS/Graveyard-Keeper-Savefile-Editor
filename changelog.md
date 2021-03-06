0.1.7
=====

Fixed:

* Items / Images (removed / renamed / added items, images)
* Small bug considering the existance of multiple entries in a list, see more here https://github.com/NetroScript/Graveyard-Keeper-Savefile-Editor/commit/8c0bd69a8df75e09202be00586afee39ed0b7e6f
* Fixing wrong character in object leading to errors when adding items to external storage
* Wrong usage of JQuery leading to the state of the checkbox being read incorrectly

Added:
* In the settings menu you can now choose your own port. Additionally you are now able to edit the settings again without deleting the settings file.
* You can now remove item drops from the map. (Intended to reduce lag if you have tons of them somewhere)
 
Improved:
* Wait for input on exception so it is easier to report errors
* Save NaN as null in the JSON so it can be parsed by strict parsers
* More comments for the source code
* Loading circle in the editor so the user knows when he can edit a specific save
* Removed content which wasn't working (perks - now you can only look at them :v)

0.1.6
=====

Fixed:

* Items which contain `(` in their names
* Many items
  * Removing / adding item names according to their qualities
  * Deleting item images which are not really needed
  * Adding new items to the editor autocomplete (Wooden planks, Fake coins, Instructions for the key, Cleric's Beginner's Guide)
  * Adding some missing images (of items)
  * Fixing some names of items
* Save issues when the inventory was empty
 
0.1.5
=====

Fixed:

* A mistake on my side which partly breaks your save file, which was introduced in 9c8be820dba71381a4e4fce4ed64813a39881400 - It is only a small change but an own release because it breaks save files. If your save file was broken by this bug, leave me a message because the fix is rather simple (it is just adding a byte at a specific location).

 
0.1.4
=====

Added:
 * Support for modifying NPC Relationship values


0.1.3
=====

Fixed:
 * Bug causing some strings to be saved again in the wrong way. It is strongly advised to update because otherwise you will lose f.e. Comfort of Faith technology after every modification


0.1.2
=====

Added:
 * You can now edit and view every storage unit (like trunks, chests, ...)
 * The information about a new update available now also displays the changes
 

Fixed:
 * Some HTML formatting
 * Some items names / icons, including but not limited to restoration tools, coal, clay, jointing, water, simple iron parts, complex iron parts, ...


0.1.1
=====

Added:
 * Support for item qualities
 * Rightful Citizen Papers so you can add them to your save if they were missing
 

Fixed:
 * Added some item id's
 * Fixed a typo in the Github URL leading to 404
 * The church quality and graveyard quality being swapped
 * Error which happens when using the application on an early savegame
