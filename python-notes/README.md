## What is Python?

Python is both compiled and interpreted, object-oriented, high level programming language with dynamic semantics.

## Features of Python

- Dynamically Typed
- GUI programming Support
- Extensible
- Large Standard Library
- Free and Open Source
- Cross Platform Language
- Interpreted Language
- Easy to Learn & Use

## Constructor
- List() → Mutable
- Set() → Mutable 
- Tuple() → Immutable
- dict() → Mutable

```py
thislist = list(("apple", "banana", "cherry"))
print(thislist) # ['apple', 'banana', 'cherry']

thistuple = tuple(("apple", "banana", "cherry"))
print(thistuple) # ('apple', 'banana', 'cherry')

thisset = set(("apple", "banana", "cherry"))
print(thisset) # {'cherry', 'apple', 'banana'}

thisdict = dict(name = "John", age = 36, country = "Norway")
print(thisdict) # {'name': 'John', 'age': 36, 'country': 'Norway'}

```

## Pip Freeze
pip freeze is a command that lists all installed Python packages and their versions in your current environment.

```python
# View all installed packages
  pip freeze

# Save the list to a file (commonly requirements.txt)
  pip freeze > requirements.txt
```

## `is vs ==`
```py
lst = ['adi', 'adi1', 'adi2']
lst2 = ['adi', 'adi1', 'adi2']

lst == lst2 # True --> check whether values are the same or not.

lst is lst2 # False --> check whether memory are same or not.

lst = ['adi', 'adi1', 'adi2']
lst2 = lst

lst is lst2 # True
lst2 is lst # True 
# This is because lst and lst2 both have same memory location
```
