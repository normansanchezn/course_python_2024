It's a type of variable.

- It doesn't have a key-value pair, so I can tell it's a set.
- It doesn't accept duplicate elements.

```
set_countries = {'col', 'mex', 'bol'} print (set_countries)
```

If I input something repeated, he removes it when printing.
```
set_countries2 = {'col', 'mex', 'bol', 'col'} print (set_countries2) # {'col', 'mex', 'bol'}
```

It can be mixed. The set sorts itself out; what matters is what I have inside.
```
set_types = {1, 'hola', False, 12.12} print(set_types) # {False, 1, 12.12, 'hola'}
```

We can create it from a tuple.
```
set_from_tuples = set (('abc','cbv','as','abc')) print (set_from_tuples) # {'as', 'abc', 'cbv'}
```

We can create it from a list.
```
numbers = [1,2,3,1,2,3,4] 
set_numbers= set(numbers) 
print (set_numbers)
```

If I want to convert this unique set to a list, I can do it:
```
unique_numbers = list(set_numbers) print (unique_numbers)
```