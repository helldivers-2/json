# Reward Types


## dictionary
This json contains a dictionary of key: value pairs, representing 
the reward information returned from the Helldivers 2 Assignment API.

![reward_type_json_image.png](reward_type_json_image.png)

### Keys
The key values of the dictionary will be the value that is assigned
in the api. In the file you can see that a key of "1" has been
assigned to the value "Medals", as that is what is shown in the API.

![mo_reward_type_highlighted.png](mo_reward_type_highlighted.png)

### Values
The value that is mapped to each key is derived from in-game
observation, as well as from known entries in the items JSON.
For example, we have derived that the key "1" is Medals as
when in-game, the Major Order was providing 50 Medals.

![mo_reward_amount_highlighted.png](mo_reward_amount_highlighted.png)
