# Armor List

## dictionary
This json contains a dictionary of key: value pairs, representing the armors within the game. These were manually
constructed from the HD2 Items API, as well as manual mapping from what we are able to find in game.

![Agent of Oblivion Cape JSON](item_armor_list_single.png)

### Key
The key values of the dictionary is the item_id of the item.


### Value
The values of each Key are a Dictionary containing the information we've been able to compile about that armor.

#### - Keys
Each Key in the value represents an attribute of the armor. 

#### - Values
Name and Description being Strings, with slot and passive being references to their respective json files. 
Type is the weight class of the armor, with 0 being light, 1 being medium, and 2 being heavy.
All helmets and Capes are classified as medium.
Armor Rating, Speed, and Stamina Regen all come from what we've been able to see in-game.



