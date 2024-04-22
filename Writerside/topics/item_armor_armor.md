# Armor List

## dictionary
This json contains a dictionary of key: value pairs, representing the armors within the game. These were manually
constructed from the HD2 Items API, as well as manual mapping from what we are able to find in game.

```json
{
  "012345": { // itemID of Armor.
    "name": "Name of the Armor",
    "description": "Armor Description.",
    "type": 1, // Type of Armor (Light(0) Medium(1) Heavy(2))
    "slot": 1, // Slot identifier. Key of slot.json
    "armor_rating": 100,
    "speed": 100,
    "stamina_regen": 100,
    "passive": 0 // Passive identifier. Key of passives.json
  }
}
```

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



