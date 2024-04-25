# Task Types

## dictionary
This json contains a dictionary of key: value pairs, representing the task information returned from the Helldivers 2 
Assignment API.

```json
{
  "3": "Eradicate",
  "11": "Liberation",
  "12": "Defense",
  "13": "Control"
}
```
```json
{
  "tasks": [
    {
      "type":       12, // <- This one
      "values":     [10, 0,  0,  0],
      "valueTypes": [ 3, 1, 11, 12]
    }
  ]
}
```

### Keys
The key values of the dictionary will be the value that is assigned in the api. In the file you can see that a key of 
"12" has been assigned to the value "Defense", as that is what is shown in the API.

```json
{
  "12" // <- The key, which corresponds to the integer in the "type" field above.
}
```

### Values
The value that is mapped to each key is derived from in-game observation. For example, we have derived that the key "12"
is Defense as when in-game, the Major Order was a Defense MO.

```json
{
  "12": "Defense" // <- The value we assigned based off our observations
}
```