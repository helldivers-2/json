# Secondary

## dictionary
This json contains a dictionary of key: value pairs, with the keys representing the weapon itemIds, with the values
being a dictionary containing weapon attributes.

```json
{
  "1": { // <- Weapon Item ID
    "name": "Secondary Weapon Name",
    "description": "Secondary Weapon Description ",
    "damage": 60,
    "capacity": 15,
    "recoil": 22,
    "fire_rate": 900,
    "fire_mode": [ // <- Array of keys in fire_modes.json for each fire mode this weapon has.
      0
    ],
    "traits": [ // <- Array of keys in traits.json for each train this weapon has.
      1,
      4
    ]
  }
}
```