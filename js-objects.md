# <span style="color: #00D100">Python Dictionaries</span>

### - In Python, dictionaries are variables that can store multiple key-value pairs.

## <span style="color:#00D100">Example</span>

```python
person = {
    "first_name": "John",

    "last_name": "Doe",
    
    "age": 45
}

# Function to get full name

def full_name(p):

    return p["first_name"] + " " + p["last_name"]

print(full_name(person))  # Output: John Doe
```