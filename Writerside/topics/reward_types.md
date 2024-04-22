# Reward Types


## dictionary
This json contains a dictionary of key: value pairs, representing 
the reward information returned from the Helldivers 2 Assignment API.

```json
{
  "1": "Medals"
}
```

```json
[
  {
    "setting": {
      "reward": {
        "type": 1, // <- 'type' - indicator of item type of reward
        "id32": 897894480, // <- itemId of rewarded item
        "amount": 50 // <- Amount of rewarded item.
      }
    }
  }
]
```

### Keys
The key values of the dictionary will be the value that is assigned
in the api. In the file you can see that a key of "1" has been
assigned to the value "Medals", as that is what is shown in the API.

```json
{
  "1" // <- Key that corresponds to the value(s) of the "type" field.
}
```

### Values
The value that is mapped to each key is derived from in-game
observation, as well as from known entries in the items JSON.
For example, we have derived that the key "1" is Medals as
when in-game, the Major Order was providing 50 Medals.

```json
{
  "1": "Medals" // <- The value we assigned based off our observations
}
```