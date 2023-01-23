#very-easy
#### [28. Burglary Series (14): Adjectives Total](https://edabit.com/challenge/jKAjLk5epb8XDzTwC)

#arrays #objects

```python
def total_amount_adjectives(dic):
    return len(dic.values())
```

**another solution**

```python
def total_amount_adjectives(dic):
    count = 0
    for i in enumerate(dic):
        count += 1
    return count
```

#easy
#### [29. Circle or Square](https://edabit.com/challenge/4me7LifXBwj5rhL4n)

#geomethry #validation

```python
import math
def circle_or_square(rad, area):
    side_length = (math.sqrt(area)) 
    if (2 * 3.14 * rad) > (4 * side_length):
        return True
    else:
        return False
```

#medium
#### [30. Drunken Python](https://edabit.com/challenge/pfn6QRn6eiTHEPpSs)

#algorithms #numbers #strings

```python
def int_to_str(num):
	return int(num)	
	
def str_to_int(num):
    return str(num)	
```

