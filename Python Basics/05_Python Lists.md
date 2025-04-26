- Lists are used to store multiple items in a single variable.
- Lists are created using square brackets:
- List items are indexed, the first item has index `[0]`, the second item has index `[1]` etc.
Lists - 
- Changeable
- Ordered

- Since lists are indexed, lists can have items with the same value:
```
thislist = ["apple", "banana", "cherry", "apple", "cherry"]  
print(thislist)
```

- To determine how many items a list has, use the `len()` function:
```
thislist = ["apple", "banana", "cherry"]  
print(len(thislist))
```
- List items can be of any data type
- A list can contain different data types
```
thislist = list(("apple", "banana", "cherry")) # note the double round-brackets  
print(thislist)
```
- `list()` to make lists
## Access Items
Print the second item of the list:

```
thislist = ["apple", "banana", "cherry"]  
print(thislist[1])
```
 
**Negative indexing-**
Print the last item of the list:

```
thislist = ["apple", "banana", "cherry"]  
print(thislist[-1])
```

##  Change List Items
- **To change the value of a specific item, refer to the index number**:

```
thislist = ["apple", "banana", "cherry"]  
thislist[1] = "blackcurrant"  
print(thislist)

```

- **To change the value of items within a specific range**
 Change the values "banana" and "cherry" with the values "blackcurrant" and "watermelon":
```
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "mango"]  
thislist[1:3] = ["blackcurrant", "watermelon"]  
print(thislist)
```
