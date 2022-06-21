## List
A data structure that is mutable (changeable) ordered sequencce of elements. Defined by having values between square brackets []

Ex:
```python
groceryList = ["pie", "potatoes", "dino nuggies", "chicken tenders" "apples", "melon"] # List of Strings
```

### Indexing List
Each item in a list corresponds to an index number, which is an integer, starting with 0.

Ex:

`groceryList[3]` outputs --> chicken tenders

`len()` gives us the length/number of items in our list

`len(groceryList)` --> 7

### List Functions
List.append(element) --> Adds an item to the end of a list

`grocerList.append("bacon")`

Ex:
```python
item = input("Enter a grocery list item: ") # whatever the user inputs
groceryList.append(item) # adds user's input to the end of the list
```
- List.insert(Index, Element) --> Add an item to the specific index location
   -`groceryList.Insert(0, "water")`
- List.remove(Element) --> Searches the list for a specific element and removes it
 - `groceryList.remove("pie")`
- List.pop(Index) --> Removes an item at specified index
 `groceryList.pop(3)`

## Random
A class that random numbers. There is a funtion that lets the computer pick a random number between a given range

## Formula
```python
import random # import the random package library

variable = random.randint(startNum, endNum)

Ex:
x = random.randint(0, 10)