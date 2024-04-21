# Primary

## dictionary
This json contains a dictionary of key: value pairs, with the keys representing the weapon itemIds, with the values
being a dictionary containing weapon attributes.

```json
{
	"1676113140": { // <- Weapon Item Id
		"name": "Primary Weapon Name",
		"description": "Primary Weapon Description.",
		"type": 1, // <- Key for types.json
		"damage": 45,
		"capacity": 30,
		"recoil": 19,
		"fire_rate": 640,
		"fire_mode": [ // <- Array of keys in fire_modes.json for each fire mode this weapon has.
			0,
			1,
			2
		],
		"traits": [ // <- Array of keys in traits.json for each train this weapon has.
			1,
			2
		]
	}
}
```