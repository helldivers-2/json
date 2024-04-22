# Value Types

## dictionary
This json contains a dictionary of key: value pairs, representing the task valueTypes information returned from the 
Helldivers 2 Assignment API. valueTypes is the indicator of what the "values" number at the same index.

```json
{
  "1": "race",
  "2": "unknown",
  "3": "goal",
  "11": "liberate",
  "12": "planet_index"
}
```

```json
[
  {
    "setting": {
      "tasks": [
        {
          "type":       12,
          "values":     [10, 0,  0,  0],
          "valueTypes": [ 3, 1, 11, 12] 
          // ^ This one tells us what the "values" values mean!
        }
      ]
    }
  }
]
```

### Keys
The key values of the dictionary will be the value that is assigned in the api. In the file you can see that a key of 
"12" has been assigned to the value "planet_index"

```json
{
  "12": // <- The key, which is a integer in the valueTypes array.
}
```

### Values
The value that is mapped to each key is derived from in-game observation. For example, we have derived that the key "12"
is planet_index as when in-game we have noticed the MO's planet's index matches what we see in the API.

There is one exception to this so far, and that is multi-planet Major Orders. When there are multiple, unspecified 
planets that are a part of one Major Order task, the planet index will have an entry of 0. It is unknown at this time
how this might conflict should we have a Major Order on Super Earth, which has a planet_index of 0, but we don't believe
it will cause any issues.  

```json
{
  "12": "planet_index" // <- The assigned value based off in-game observations.
}
```
