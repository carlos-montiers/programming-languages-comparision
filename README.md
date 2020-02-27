# programming-languages-comparison
Shows my summaries about the same concept in different programming languages

## Collections

ordered means 'preserve insertion order'.

|   | Python  |  Php | Javascript  | Golang  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Concept: Collection ordered and changeable  | List  |  Array (integer index)  | Array  | Slice  |
| Syntax  | bikes = ["trek", "redline"]  | $bikes = ["trek", "redline"]  | let bikes = ["trek", "redline"]  | bikes := []string{"trek", "redline"}  |
| Concept: Collection ordered and unchangeable  | Tuple  |   |   | Array  |
| Syntax  | resolution = (1366, 768)  |   |   | resolution := [2]int{1366, 768}  |
| Concept: Store connections between pieces of information. Each item is a key value pair  | Dictionary  | Array (string index)  | Map / Object  | Map  |
|   | 2.7 unordered / 3.6 ordered  | ordered  | map ordered / object unordered  | unordered  |
| Syntax  | prices = {"rice": 500}  | $prices = ["rice" => 500]  | let pricesMap = new Map(); pricesMap.set('rice', 500);  | prices := map[string]int{"rice": 500}  |
|  |  |  | let pricesObj = {"rice" : 500}  |  |
| Concept: Collection unordered and unindexed  | Set  |   |  Set |   |
|   | items will appear in a random order.  |   |  ordered|   |
|   | fruits = {"apple", "cherry"}  |   |  let fruits = new Set(); fruits.add("apple"); fruits.add("cherry");  |   |  |


Created by Carlos Montiers A.
