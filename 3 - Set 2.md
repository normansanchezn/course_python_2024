![[Captura de pantalla 2024-03-11 a la(s) 6.15.09 p.m..png]]
We define two sets:
```
set_a = {'col', 'mex', 'bol'} 
set_b = {'pe', 'bol'}
```

create set:
```
set_c = set_a.union(set_b)
print(set_c)
print(set_a | set_b)
```

Intersection:
```
set_c = set_a.intersection(set_b)
```

Difference:
```
set_c = set_a.difference(set_b) 
print(set_c)
print(set_a - set_b)
```

Symmetric Difference:
```
set_c = set_a.symmetric_difference(set_b) 
print(set_c)
print(set_a ^ set_b)
```