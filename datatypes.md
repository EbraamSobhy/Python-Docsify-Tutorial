# <span style="color: #00D100">Python Data Types</span>

### - Data types define the kind of data a variable can store.

---

## <span style="color:#00D100">String</span>
```python
greeting = "Hello, world!"

name = 'John Doe'

print(type(greeting))  # <class 'str'>
```

## <span style="color:#00D100">Number</span>
```python
age = 30           # Integer

price = 19.99      # Floating-point number

sum_value = age + price  # 49.99

print(type(age))   # <class 'int'>

print(type(price)) # <class 'float'>
```

## <span style="color:#00D100">Boolean</span>
```python
is_student = True

has_license = False

print(type(is_student))  # <class 'bool'>
```

## <span style="color:#00D100">None</span>
```python
first_name = None

print(first_name)        # None

print(type(first_name))  # <class 'NoneType'>
```

## <span style="color:#00D100">Dictionary (Object)</span>
```python
person = {
    "first_name": "Jane",

    "last_name": "Doe",

    "age": 28
}

print(type(person))       # <class 'dict'>

print(person["first_name"])  # "Jane"
```

## <span style="color:#00D100">List (Array)</span>
```python
colors = ["red", "green", "blue"]

print(colors[0])          # "red"

print(type(colors))       # <class 'list'>
```