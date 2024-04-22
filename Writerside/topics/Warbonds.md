# Warbonds

## dictionary
The warbond jsons all follow the same pattern found below. They are a dictionary of key: value pairs, where the key is
the page number of the warbond,  and the values of that key are the medals_to_unlock the page to be able to access that
page, and items, a Array of Dicts, where each dict is a singular item in the warbond, containing the item ID and the 
medals cost of that item.


```json
{
  "1": { // <- Warbond Page Number 
    "medals_to_unlock": 0, // <- Number of medals spent in the individual warbond to gain access to this page
    "items": [ // Array[Dict{}] for each item on the indicated page number.
      {
        "item_id": 00000, // <- Item ID of item in warbond
        "medal_cost": 0 // <- How many medals to buy this item.
      }
    ]
  }
}
```