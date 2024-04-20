# Value Types

## dictionary
This json contains a dictionary of key: value pairs, representing the task information returned from the Helldivers 2
Assignment API.  

![mo_task_valuetypes_image.png](mo_task_valuetypes_image.png)

### Keys
The key values of the dictionary will be the value that is assigned in the api. In the file you can see that a key of 
"12" has been assigned to the value "planet_index"

![mo_task_valuetypes_highlighted.png](mo_task_valuetypes_highlighted.png)

### Values
The value that is mapped to each key is derived from in-game observation. For example, we have derived that the key "12"
is planet_index as when in-game we have noticed the MO's planet's index matches what we see in the API.

There is one exception to this so far, and that is multi-planet Major Orders. When there are multiple, unspecified 
planets that are a part of one Major Order task, the planet index will have an entry of 0. It is unknown at this time
how this might conflict should we have a Major Order on Super Earth, which has a planet_index of 0, but we don't believe
it will cause any issues.  

![mo_task_values_highlighted.png](mo_task_values_highlighted.png)