# Environmentals

## dictionary
This json contains a dictionary of key: value pairs, with the keys representing the environmental hazard names, and the
values being dictionaries containing Name and Description of each known environmental hazard, with an unknown option
included for any future planets we don't have mapped yet.

```json
{
  "none": {
    "name": "None",
    "description": "This planet's environment is not yet known, or has no environmental modifiers."
  },
  "extreme_cold": {
    "name": "Extreme Cold",
    "description": "Icy temperatures reduce rate of fire and delay heat buildup in weapons."
  }
}
```