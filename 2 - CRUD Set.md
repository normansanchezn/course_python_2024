```
set_countries = {'col', 'mex', 'bol'}

# len(): Returns the size of the set
size = len(set_countries)
print(size)

# in: Allows to know if an element is in the set. The expression evaluates to true if the element is in the set and false if the element is not in the set
print('col' in set_countries)
print('pe' in set_countries)

# add(): Adds an element to the set.
set_countries.add('pe')
print(set_countries)
set_countries.add('pe')
print(set_countries)

# update(): Adds any iterable object such as lists, tuples
set_countries.update({'ar', 'ecua', 'pe'})
print(set_countries)

# remove(): Removes an element and if it does not exist it throws the error "KeyError"
set_countries.remove('col')
print(set_countries)
# set_countries.remove('ar') # This line will raise a KeyError because 'ar' doesn't exist in the set

# discard(): Removes an element and if it already exists, it does not raise any error
set_countries.discard('arg')
print(set_countries)
set_countries.add('arg')
print(set_countries)

# pop(): Returns a random element and removes it, if the set is empty, it raises the error "KeyError".
print(set_countries.pop())
print(set_countries)

# clear(): Removes all content from the set
set_countries.clear()
print(set_countries)
print(len(set_countries))

```