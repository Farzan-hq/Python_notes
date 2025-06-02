**Format specifiers**- {value:flag} format a value based on what flaga are inserted
```
price1 = 3.1456789
print(f"Price 1 is {price1:.2f}
```
Here 2 means till 2 decimal points and f means float
- if you want space allocated to display a value
```
price1 = 3.1456789
print(f"Price 1 is {price1:.6}")
```
- now to preceed a number with 0
```
price1 = 3.1456789
print(f"Price 1 is {price1:010}
```
there are other format specifiers too - https://www.w3schools.com/python/ref_string_format.asp (go to formatting types)
- u can use 2 - 3 format specifiers at once
  
