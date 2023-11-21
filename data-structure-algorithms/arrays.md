# Arrays

## Static Arrays
- Static arrays have an allocated size when initialized.
- E.g.: Java, C++, C etc
- |Operations	|Time Complexity|Notes|
  |-------------|---------------|-----------|
  |Reading	|O(1)		|\-|
  |Insertion	|O(n)*		|If inserting at the end, O(1)|
  |Deletion	|O(n)*		|If deleting at the end, O(1)|

## Dynamic Arrays
- Dynamically allocate memory size
- E.g.: Javascript, Python
- |Operations	|Time Complexity|Notes|
  |-------------|---------------|-----------|
  |Reading	|O(1)		|\-|
  |Insertion	|O(1)*		|If inserting at the middle, O(n)|
  |Deletion	|O(1)*		|If deleting at the middle, O(n)|

## Stacks
- One implementations of dynamic arrays
- Last In First Out (LIFO)
- |Operations	|Time Complexity|Notes|
  |-------------|---------------|-----------|
  |Push		|O(1)		|\-|
  |Pop		|O(1)*		|Check if the stack is empty first|
  |Peek / Top	|O(1)*		|Retrieves without removing|

