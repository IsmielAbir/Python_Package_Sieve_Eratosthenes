# PySieveEra

**PySieveEra** is a Python package that implements the Sieve of Eratosthenes algorithm to efficiently generate a list of prime numbers within a specified numerical range. This tool is useful for various mathematical and computational applications that involve prime numbers.

## Usage

```python
from PySieveEra import SieveEra

# Generate a list of prime numbers within a specified range
limit = 20
prime_numbers = SieveEra(limit)
print("Prime numbers within the range:", prime_numbers)

```

## Function Signature

```python 
SieveEra(limit=20)
```

limit (default is 20): The upper limit for generating prime numbers. Specify the maximum value up to which you want to find prime numbers.


## Output
The function returns a list of prime numbers within the specified range. You can then use this list for your specific needs.
Prime numbers within the range: [2, 3, 5, 7, 11, 13, 17, 19]